---
title: 太玄筮法 - A Python package
summary: An alternative Iching divination tool name Tai Xuan created by a Chinese Confucian Yang Xiong (BC53 - 18CE) from Xi Han Dynasty.
tags:
- Python
date: "2020-01-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Github
  url: https://github.com/kentang2017/taixuanshifa

- icon: python
  icon_pack: fab
  name: PYPI
  url: https://pypi.org/project/taixuanshifa

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


## **1. Introduction 導讀**︰

An alternative Iching divination tool named TaiXuan created by a Chinese Confucian Yang Xiong (BC53 - 18CE) from Xi Han Dynasty.

《太玄》，又稱《太玄經》、《揚子太玄經》或《玄經》，是西漢學者揚雄的一部著作，用來闡述他的哲學體系和宇宙論。《四庫全書》中為避康熙皇帝的名諱，改稱其為《太元經》。《新唐書·藝文志》作十二卷，《文獻通考》作十卷。

《太玄》糅合了儒家、道家和陰陽家的學說。其首先從《老子》「玄之又玄」中概括出「玄」（玄奧）的概念，以玄為中心，按天地人三道的分類建立了一個形上學體系。《太玄》認為一切事物從發展到旺盛到消亡都可分成九個階段。

唐朝詩人李白的《俠客行》最後一句「白首太玄經」，即指此書。

![alt text](https://github.com/kentang2017/taixuanshifa/blob/master/data/pic.png?raw=true)
太元方州部家八十一首圖

## **2. Installation 安裝套件**

```python
	pip install taixuanshifa
```

## **3. Start Divination 起卦**
```python
	from taixuanshifa import taixuanshifa
	
	taixuanshifa.qigua( )
	{'卦': {'眾': '陽氣信高懷齊，萬物宣明嫭大眾多。'}, '初一': '冥兵始，火入耳，農輟馬穀，尸將班于田。測曰，「冥兵」之「始」、始則不臧也。', '次二': '兵無刃，師無陳，麟或賓之，溫。測曰，「兵無刃」、德服無方也。', '次三': '軍或纍車，丈人摧孥，內蹈之瑕。測曰，「軍或纍車」、廟戰內傷也。', '次四': '虎虓振廞，豹勝其祕否。測曰，「虎虓振廞」、如鷹之揚也。', '次五': '躆戰喈喈，若熊若螭。測曰，「躆戰喈喈」、恃力作王也。', '次六': '大兵雷霆，震其耳，維用詘腹。測曰，「大兵雷霆」、威震無疆也。', '次七': '旌旗絓羅，干戈蛾蛾，師孕言之，哭且䁲。測曰，「旌旗絓羅」、大恨民也。', '次八': '兵衰衰，見其病，不見輿尸。測曰，「兵衰衰」、不血刃也。', '上九': '斧刃缺，其柯折，可以止，不可以伐，往血。測曰，「刃缺」「柯折」、將不足往也。'}
	
	
```

