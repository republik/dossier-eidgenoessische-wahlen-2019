---
template: dossier
slug: wahlen
feed: true
gallery: true
title: "Eidgenössische Wahlen\_2019"
subject: ''
description: Lead
---

<section><h6>TITLE</h6>

# Eidgenössische Wahlen 2019

## 

Lead

Von [Andreas Moor](/~65b64225-3843-4e41-a7a6-716ae81a5d57), 02.10.2019

<hr /></section>

<section><h6>CENTER</h6>

Die Schweiz wählt alle vier Jahre alle Sitze in beiden Kammern des Parlaments neu. 

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "values": [
      {
        "label": "Kandidierende",
        "value": "4735",
        "unit": "",
        "description": "Anzahl Kandidatinnen und Kandidaten für 246 Sitze in National- und Ständerat",
        "source": {
          "name": "Republik Wahltindär",
          "url": "https://www.republik.ch/wahltindaer",
          "date": "01.10.2019"
        },
        "color": "rgb(187,21,26)"
      },
      {
        "label": "Kandidatinnen",
        "value": "40,3%",
        "unit": "",
        "description": "Frauenanteil bei den Kandidierenden für den Nationalrat",
        "source": {
          "name": "BFS",
          "url": "https://www.bfs.admin.ch/bfs/de/home/statistiken/kataloge-datenbanken/tabellen.assetdetail.9466387.html",
          "date": "30.09.2019"
        },
        "color": "rgb(187,21,26)"
      },
      {
        "label": "Stimmberechtigte",
        "value": "5,4 Mio.",
        "unit": "",
        "description": "Anzahl Stimmberechtigte",
        "source": {
          "name": "BFS",
          "url": "https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/abstimmungen/stimmbeteiligung.assetdetail.7646490.html",
          "date": "23.10.2018"
        },
        "color": "rgb(187,21,26)"
      },
      {
        "type": "timer",
        "label": "Zeit bis zur Wahl",
        "value": 1571652000000,
        "description": "Verbleibende Zeit bis zur Schliessung der Wahllokale am 21. Oktober um 12:00",
        "color": "rgb(187,21,26)"
      }
    ]
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/indicators.js?v2.7",
  "size": "breakout"
}
```

<hr /></section>

Lorem ipsum dolor.

<section><h6>CHART</h6>

```
{
  "type": "Bar",
  "y": "year",
  "color": "party",
  "colorLegend": true,
  "colorSort": "none",
  "numberFormat": "%",
  "sort": "none",
  "domain": [
    0,
    1
  ],
  "colorRange": [
    "#3CAD00",
    "#d62728",
    "#E9A733",
    "#ff7f0e",
    "#BCBD21",
    "#2077B4",
    "#FFDD00",
    "#2BA02B",
    "#bbb"
  ]
}
```

### Erstarkende Rechte, fragmentierte Mitte

Stimmenanteile der Parteien bei Nationalratswahlen

```
year,party,value
1999,GPS,0.049664
1999,SP,0.224735
1999,EVP,0.018278
1999,CVP,0.158537
1999,GLP,0.000000
1999,FDP,0.199171
1999,BDP,0.000000
1999,SVP,0.225438
1999,Übrige,0.124178
2003,GPS,0.074324
2003,SP,0.233227
2003,EVP,0.022725
2003,CVP,0.143750
2003,GLP,0.000000
2003,FDP,0.173347
2003,BDP,0.000000
2003,SVP,0.266532
2003,Übrige,0.086094
2007,GPS,0.095861
2007,SP,0.195462
2007,EVP,0.024420
2007,CVP,0.144789
2007,GLP,0.014272
2007,FDP,0.157614
2007,BDP,0.000000
2007,SVP,0.288968
2007,Übrige,0.078614
2011,GPS,0.084328
2011,SP,0.187222
2011,EVP,0.019974
2011,CVP,0.123040
2011,GLP,0.053809
2011,FDP,0.151045
2011,BDP,0.054154
2011,SVP,0.265562
2011,Übrige,0.060865
2015,GPS,0.070571
2015,SP,0.188410
2015,EVP,0.018945
2015,CVP,0.116459
2015,GLP,0.046259
2015,FDP,0.163967
2015,BDP,0.041038
2015,SVP,0.293860
2015,Übrige,0.060493
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen.assetdetail.217191.html).

<hr /></section>

Lorem ipsum solor.

<section><h6>CHART</h6>

```
{
  "type": "Bar",
  "y": "year",
  "color": "party",
  "colorLegend": true,
  "colorSort": "none",
  "sort": "none",
  "domain": [
    0,
    46
  ],
  "colorRange": [
    "#3CAD00",
    "#d62728",
    "#ff7f0e",
    "#BCBD21",
    "#2077B4",
    "#FFDD00",
    "#2BA02B",
    "#bbb"
  ]
}
```

### Stabiles Stöckli

Sitzverteilung im Ständerat nach Parteien

```
year,party,value
1999,GPS,0.000000
1999,SP,6.000000
1999,CVP,15.000000
1999,GLP,0.000000
1999,FDP,17.000000
1999,BDP,0.000000
1999,SVP,7.000000
1999,Übrige,1.000000
2003,GPS,0.000000
2003,SP,9.000000
2003,CVP,15.000000
2003,GLP,0.000000
2003,FDP,14.000000
2003,BDP,0.000000
2003,SVP,8.000000
2003,Übrige,0.000000
2007,GPS,2.000000
2007,SP,9.000000
2007,CVP,15.000000
2007,GLP,1.000000
2007,FDP,12.000000
2007,BDP,0.000000
2007,SVP,7.000000
2007,Übrige,0.000000
2011,GPS,2.000000
2011,SP,11.000000
2011,CVP,13.000000
2011,GLP,2.000000
2011,FDP,11.000000
2011,BDP,1.000000
2011,SVP,5.000000
2011,Übrige,1.000000
2015,GPS,1.000000
2015,SP,12.000000
2015,CVP,13.000000
2015,GLP,0.000000
2015,FDP,13.000000
2015,BDP,1.000000
2015,SVP,5.000000
2015,Übrige,1.000000
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/staenderatswahlen.assetdetail.81547.html).

<hr /></section>

Lorem ipsum.

<section><h6>CHART</h6>

```
{
  "type": "TimeBar",
  "y": "value",
  "unit": "%",
  "numerFormat": "%",
  "xTicks": [
    "1919",
    "1963",
    "1999",
    "2015"
  ],
  "colorRange": [
    "rgb(187,21,26)"
  ]
}
```

### Einpendeln oder Trendwende?

Wahlbeteiligung bei Nationalratswahlen seit 1919

```
year,value
1919,80.3787
1922,76.3659
1925,76.8011
1928,78.7863
1931,78.8259
1935,78.3118
1939,74.2935
1943,70.0426
1947,72.4390
1951,71.2001
1955,70.0762
1959,68.4628
1963,66.1072
1967,65.7195
1971,56.8564
1975,52.3620
1979,48.0464
1983,48.9061
1987,46.4684
1991,46.0457
1995,42.2222
1999,43.3031
2003,45.2310
2007,48.2761
2011,48.5048
2015,48.5100
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen/wahlbeteiligung.assetdetail.217210.html).

<hr /></section>

Lorem ipsum dolor.

<hr /></section>
