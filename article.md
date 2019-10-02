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

Lorem ipsum dolor.

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
  "numberFormat": "%",
  "sort": "descending",
  "domain": [
    0,
    100
  ]
}
```

### Erstarkende Rechte, fragmentierte Mitte

Stimmenanteile der Parteien bei Nationalratswahlen

```
year,party,value
1995,FDP,20.18
1995,CVP,16.79
1995,SP,21.79
1995,SVP,14.90
1995,GLP,0.00
1995,GPS,5.04
1995,Andere,21.29
1999,FDP,19.92
1999,CVP,15.85
1999,SP,22.47
1999,SVP,22.54
1999,GLP,0.00
1999,GPS,4.97
1999,Andere,14.25
2003,FDP,17.33
2003,CVP,14.37
2003,SP,23.32
2003,SVP,26.65
2003,GLP,0.00
2003,GPS,7.43
2003,Andere,10.88
2007,FDP,15.76
2007,CVP,14.48
2007,SP,19.55
2007,SVP,28.90
2007,GLP,1.43
2007,GPS,9.59
2007,Andere,10.30
2011,FDP,15.10
2011,CVP,12.30
2011,SP,18.72
2011,SVP,26.56
2011,GLP,5.38
2011,GPS,8.43
2011,Andere,13.50
2015,FDP,16.40
2015,CVP,11.65
2015,SP,18.84
2015,SVP,29.39
2015,GLP,4.63
2015,GPS,7.06
2015,Andere,12.05
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen.assetdetail.217191.html).

<hr /></section>



<hr /></section>
