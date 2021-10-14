---
title: 堅六壬
summary: Dailiuren (大六壬) is one of the three greatest Chinese Divination systems ever.
tags:
- Python
date: "2020-01-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/kentang2017/kinliuren

- icon: python
  icon_pack: fab
  name: PYPI
  url: https://pypi.org/project/kinliuren

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/2/22/%E7%BA%8C%E4%BF%AE%E5%9B%9B%E5%BA%AB%E5%85%A8%E6%9B%B8%E7%AC%AC1057%E5%86%8A.pdf/page568-428px-%E7%BA%8C%E4%BF%AE%E5%9B%9B%E5%BA%AB%E5%85%A8%E6%9B%B8%E7%AC%AC1057%E5%86%8A.pdf.jpg "六壬軍帳神機")

## 1. 導讀 Introduction
大六壬，或稱六壬神課，簡稱六壬，是中國古老三大占卜術之一。大六壬與奇門遁甲、太乙神數並稱三式。大六壬盛行於漢朝、三國、魏晉南北朝，文人名士多有以此為休閒，常以懷中藏物互相占卜猜測，名曰「射覆」。唐宋以來，明清相繼，相承至今。然六壬演式繁雜，主要在士大夫之間流傳，在民間社會中漸被文王卦所代替。當今社會，在中國大陸、香港和台灣均有一部分人在研習六壬。六壬術傳至日本後，在平安時代由陰陽師安倍晴明發揚光大。為現代算命相術之一。

Da Liu Ren is a form of Chinese calendrical astrology dating from the later Warring States period. It is also a member of the Three Styles (三式; sānshì; 'three rites') of divination, along with Qi Men Dun Jia (奇门遁甲) and Taiyi (太乙).

In the words of a contemporary Chinese master of Da Liu Ren, the six rén indicate an entire movement of the sexagenary cycle, during which an something may appear, rise to maturity and then decline and disappear. Thus the six rén indicate the life cycle of phenomena. There is a homonym in the Chinese language which carries the meaning of pregnancy and so the six rén also carry the meaning of the birth of a phenomenon.

## 2. 安裝套件 Installation
```python
	pip install kinliuren
```
## 3. 起課方式 Quickstart
```python
	from kinliuren import kinliuren
	kinliuren.Liuren( 節氣, 日干支, 時干支).result(0)
	例如 Liuren("冬至", "丁未", "乙巳")
{'節氣': '冬至', '日期': '丁未日乙巳時', '格局': ['賊尅', '元首'], '三傳': {'初傳': ['卯', '勾陳', '父母', '空'], '中傳': ['亥', '貴人', '官鬼', '辛'], '末傳': ['未', '太常', '子孫', '丁']}, '四課': {'四課': ['亥卯', '貴人'], '三課': ['卯未', '勾陳'], '二課': ['亥卯', '貴人'], '一課': ['卯丁', '勾陳']}, '天地盤': {'天盤': ['丑', '寅', '卯', '辰', '巳', '午', '未', '申', '酉', '戌', '亥', '子'], '地盤': ['巳', '午', '未', '申', '酉', '戌', '亥', '子', '丑', '寅', '卯', '辰'], '天將': ['朱雀', '六合', '勾陳', '青龍', '天空', '白虎', '太常', '玄武', '太陰', '天后', '貴人', '螣蛇']}, '地轉天盤': {'巳': '丑', '午': '寅', '未': '卯', '申': '辰', '酉': '巳', '戌': '午', '亥': '未', '子': '申', '丑': '酉', '寅': '戌', '卯': '亥', '辰': '子'}, '地轉天將': {'巳': '朱雀', '午': '六合', '未': '勾陳', '申': '青龍', '酉': '天空', '戌': '白虎', '亥': '太常', '子': '玄武', '丑': '太陰', '寅': '天后', '卯': '貴人', '辰': '螣蛇'}}
```

