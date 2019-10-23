---
twitterTitle: "Daten, Fakten –\_und ein Best-of der Republik-Beiträge"
twitterImage: images/b06c06835694fa8e114bb54e6cfc49501ceff76e.png?size=1204x604
slug: wahlen2019
subject: ''
facebookTitle: "Daten, Fakten –\_und ein Best-of der Republik-Beiträge"
gallery: true
facebookImage: images/140a0a8f18ccd1179e52505c9c5d3d3f4f615f70.png?size=1204x630
title: "Dossier: Wahlen\_2019"
template: dossier
feed: true
---

<section><h6>TITLE</h6>

# Wahlen 2019

## 

⁣

Letzte Aktualisierung: 22.10.2019

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "values": [
      {
        "label": "Offene Sitze im Ständerat",
        "value": "22",
        "unit": "",
        "description": "Anzahl Ständeratssitze, die einen zweiten Wahlgang benötigen",
        "source": {
          "name": "BFS",
          "url": "https://www.wahlen.admin.ch/de/ch/",
          "date": "20.10.2019"
        },
        "color": "#39bbcc"
      },
      {
        "label": "Frauenanteil Nationalrat",
        "value": "42%",
        "unit": "",
        "description": "Frauenanteil bei den gewählten Kandidierenden für den Nationalrat",
        "source": {
          "name": "BFS",
          "url": "https://opendata.swiss/de/dataset/eidg-wahlen-2019/resource/6c6d3453-0aa3-4e2b-89b3-ed100ea5acee",
          "date": "20.10.2019"
        },
        "color": "#39bbcc"
      },
      {
        "label": "Wahlberechtigte",
        "value": "5’457’940",
        "unit": "",
        "description": "Anzahl Wahlberechtigte",
        "source": {
          "name": "BFS",
          "url": "https://opendata.swiss/de/dataset/eidg-wahlen-2019/resource/3be5b54e-8c21-40c9-8e36-fbffb5638352",
          "date": "20.10.2019"
        },
        "color": "#39bbcc"
      },
      {
        "label": "Wahlbeteiligung",
        "value": "45,1%",
        "unit": "",
        "description": "Anteil der Wählenden an den Wahlberechtigten",
        "source": {
          "name": "BFS",
          "url": "https://opendata.swiss/de/dataset/eidg-wahlen-2019/resource/3be5b54e-8c21-40c9-8e36-fbffb5638352",
          "date": "20.10.2019"
        },
        "color": "#39bbcc"
      }
    ]
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/indicators.js?v3.4",
  "size": "breakout"
}
```

<hr /></section>

## Nationalrat

Im Nationalrat verzeichneten die Parteien mit ökologischem Schwer­punkt massive Sitzgewinne: Die Grüne Partei erzielte mit einem Plus von 6,1 Prozent­punkten ihr bislang bestes Ergebnis. Sie gewann 17 Sitze dazu. Mit 28 Sitzen wurde sie so zur viertstärksten Kraft im Nationalrat. Die Grünliberalen gewannen 9 Sitze hinzu und entsenden neu 16 Vertreter in die grosse Kammer. Beide Parteien schnitten weit besser ab als in [der letzten Umfrage vor der Wahl](https://www.srf.ch/news/schweiz/wahlen-2019/klimafrage-spaltet-die-waehler-liberaler-ueberdruss-und-linke-euphorie).

Auf der Verliererseite stand in erster Linie die SVP: Sie büsste 12 Sitze ein und erreichte neu nur noch 53 Nationalräte. Die Partei fuhr mit einem Wähler­anteil von 25,6 Prozent ihr schlechtestes Resultat seit 2003 ein und beendete eine langjährige Erfolgs­strähne, in der sie ihren Wähleranteil 2015 auf 29,4 Prozent steigern konnte – und dies, obwohl sich 2008 die BDP von ihr abgespaltet hatte. Letztere verlor bei den Wahlen 4 Sitze und erreichte mit den verbleibenden 3 Nationalräten nicht mehr Fraktionsstärke.

Die SP sank in der Wählergunst unerwartet stark auf 16,8 Prozent (–2) und erreicht mit 39 Sitzen (–4) ihr schlechtestes Resultat seit der Einführung der Proporz­wahl im Jahr 1919, als sie mit 41 Sitzen in den Nationalrat einzog.

Auch die FDP musste starke Verluste hinnehmen: Sie verlor 1,3 Prozent­punkte und liegt nur noch rund 2 Prozent­punkte vor den Grünen. Damit setzt der Freisinn seinen Niedergang fort, der ihn von 60 Sitzen im Jahr 1919 auf heute nur noch 29 schrumpfen liess. Die CVP verlor 3 Sitze und landete mit 25 Abgeordneten ebenfalls auf einem neuen Tiefststand – dies trotz einem moderaten Verlust von 0,2 Prozentpunkten.

<section><h6>CHART</h6>

```
{
  "type": "Hemicycle",
  "unit": "Sitze"
}
```

### Sitzverteilung im Nationalrat

Eidgenössische Wahlen 2019

```
label,year,value
PdA,2019,1,
Sol,2019,1
SP,2019,39
GPS,2019,28,
GLP,2019,16
EVP,2019,3
CVP,2019,25
BDP,2019,3
FDP,2019,29
SVP,2019,53
Lega,2019,1
EDU,2019,1
PdA,2015,1
SP,2015,43
GPS,2015,11
GLP,2015,7
EVP,2015,2
CVP,2015,27
BDP,2015,7
FDP,2015,33
SVP,2015,65
Lega,2015,2
MCR,2015,1
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen.html).

<hr /></section>

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
  "xTicks": [
    0,
    1
  ],
  "colorRange": [
    "#F0554D",
    "#84B547",
    "#C4C43D",
    "#D6862B",
    "#E6C820",
    "#3872B5",
    "#4B8A3E",
    "#A09E9C"
  ]
}
```

### Wähleranteile bei Nationalratswahlen

Bei eidgenössischen Wahlen seit 1987

```
year,party,value
2019,SP,0.1684
2019,GPS,0.1320
2019,GLP,0.0780
2019,CVP,0.1138
2019,BDP,0.0244
2019,FDP,0.1511
2019,SVP,0.2559
2019,Übrige,0.0764
2015,SP,0.188410
2015,GPS,0.070571
2015,GLP,0.046259
2015,CVP,0.116459
2015,BDP,0.041038
2015,FDP,0.163967
2015,SVP,0.293860
2015,Übrige,0.079438
2011,SP,0.187222
2011,GPS,0.084328
2011,GLP,0.053809
2011,CVP,0.123040
2011,BDP,0.054154
2011,FDP,0.151045
2011,SVP,0.265562
2011,Übrige,0.080839
2007,SP,0.195462
2007,GPS,0.095861
2007,GLP,0.014272
2007,CVP,0.144789
2007,BDP,0.000000
2007,FDP,0.157614
2007,SVP,0.288968
2007,Übrige,0.103034
2003,SP,0.233227
2003,GPS,0.074324
2003,GLP,0.000000
2003,CVP,0.143750
2003,BDP,0.000000
2003,FDP,0.173347
2003,SVP,0.266532
2003,Übrige,0.108820
1999,SP,0.224735
1999,GPS,0.049664
1999,GLP,0.000000
1999,CVP,0.158537
1999,BDP,0.000000
1999,FDP,0.199171
1999,SVP,0.225438
1999,Übrige,0.142455
1995,SP,0.217929
1995,GPS,0.050421
1995,GLP,0.000000
1995,CVP,0.167936
1995,FDP,0.201811
1995,BDP,0.000000
1995,SVP,0.149005
1995,Übrige,0.212898
1991,SP,0.184907
1991,GPS,0.060735
1991,GLP,0.000000
1991,CVP,0.179995
1991,BDP,0.000000
1991,FDP,0.209908
1991,SVP,0.119010
1991,Übrige,0.245446
1987,SP,0.184169
1987,GPS,0.048788
1987,GLP,0.000000
1987,CVP,0.195829
1987,BDP,0.000000
1987,FDP,0.229325
1987,SVP,0.110240
1987,Übrige,0.231649
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen.assetdetail.217191.html).

<hr /></section>

## Ständerat

Im Ständerat sind fast die Hälfte der Sitze noch nicht endgültig vergeben. Diese werden in zweiten Wahlgängen bis Ende November besetzt. Es ist zu erwarten, dass die kleine Kammer weiterhin bürgerlich geprägt sein wird. Ebenfalls zeichnet sich ab, dass deutlich mehr Frauen im neuen Ständerat Einsitz nehmen werden.

<section><h6>CHART</h6>

```
{
  "type": "Hemicycle",
  "inlineLabelThreshold": 4,
  "unit": "Sitze",
  "size": "narrow",
  "colorMap": {
    "SP": "#F0554D",
    "GPS": "#84B547",
    "CVP": "#D6862B",
    "BDP": "#E6C820",
    "FDP": "#3872B5",
    "SVP": "#4B8A3E",
    "PARTEILOS": "#A09E9C",
    "OFFEN": "#eee"
  }
}
```

### «Stöckli» noch offen

Sitzverteilung im Ständerat

```
label,year,value
SP,2019,3
GPS,2019,2
CVP,2019,8
FDP,2019,7
SVP,2019,3
parteilos,2019,1
Offen,2019,22
SP,2015,12
GPS,2015,1
CVP,2015,13
BDP,2015,1
FDP,2015,13
SVP,2015,5
parteilos,2015,1
```



<hr /></section>

## Wahlbeteiligung

Bei den Wahlen im Oktober 2019 gaben 45,1 Prozent der Wahlberechtigten ihre Stimme ab – 3,4 Prozentpunkte weniger als bei den Wahlen 2015.

Die Wahlbeteiligung sank von 1935 bis 1995 stetig. Vor dem Zweiten Weltkrieg liessen sich noch vier Fünftel des Stimm­volkes für die Nationalrats­wahlen an die Urnen bewegen, 1995 waren es nur noch halb so viele. Bis zu den Wahlen 2015 zeichnete sich wieder eine leichte Erholung ab – damals gaben wieder 48,5 Prozent der Wahl­berechtigten ihre Stimme ab.

<section><h6>CHART</h6>

```
{
  "y": "value",
  "unit": "%",
  "numberFormat": ".1f",
  "xTicks": [
    "1935",
    "1951",
    "1967",
    "1983",
    "1999",
    "2019"
  ],
  "yTicks": [
    0,
    50,
    100
  ],
  "xIntervalStep": 4,
  "colorRange": [
    "#39bbcc"
  ],
  "size": "narrow",
  "type": "Line"
}
```

### Wahlbeteiligung

Nationalratswahlen seit 1935

```
year,value
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
2019,45.1
```

Quelle: [BFS](https://opendata.swiss/de/dataset/eidg-wahlen-2019/resource/3be5b54e-8c21-40c9-8e36-fbffb5638352).

<hr /></section>

## Ausblick

Die erste Session der 51. Legislatur der Bundes­versammlung (2019–2023) wird vom 2. bis 20. Dezember stattfinden. Am 11. Dezember steht ein wichtiges Traktandum an: die Gesamt­erneuerungs­wahl des Bundesrates. Zahlreiche Heraus­forderungen sorgen dafür, dass dem Parlament in den nächsten Jahren die Arbeit nicht ausgeht: [Klima, Digitalisierung, Gesundheit, Renten, Europa, Gleichstellung, Energiepolitik](https://github.com/republik/article-klimapolitik?autoSlug "Die grosse Abrechnung") – die Liste ist nicht abschliessend.

<section><h6>INFOBOX</h6>

### Zum Dossier Wahlen 2019

Das Dossier bündelt wissens­werte Fakten und eine Auswahl von Republik-Beträgen zu den eidgenössischen Wahlen am 20. Oktober 2019. Alle Quellen und Original­daten sowie die Methoden ihrer Aufbereitung [sind hier dokumentiert](https://github.com/republik/dossier-eidgenoessische-wahlen-2019) (einschliesslich eines [Protokolls der Aktualisierungen](https://github.com/republik/dossier-eidgenoessische-wahlen-2019/commits/master)).

<hr /></section>

## Ausgewählte Beiträge der Republik:



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#000",
      "author": "Von der <a href='/impressum'>Republik-Redaktion</a>, 21.10.2019",
      "url": "https://www.republik.ch/wahltindaer/bundesversammlung",
      "title": "Das neue Parlament",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/magazine/images/487d641a65654a03295dbec63c5f4eb904cf8af2.jpeg",
      "lead": "Alle Gewählten im Republik Wahltindär.",
      "bgColor": "#DAFFCA"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-briefing-spezial-wahlen-2019?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-briefing-aus-bern?autoSlug",
  "titleSize": "standard",
  "id": "XpyxX_w2S",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Briefing aus Bern

# Klima, Linksrutsch, Frauenwahl – was Sie zu diesen Wahlen wissen müssen

## 

#### Das Sonderbriefing aus Bern zu den eidgenössischen Wahlen.

Von [Ronja Beck](/~robeck "Ronja Beck"), [Oliver Fuchs](/~ofuchs "Oliver Fuchs") und [Andreas Moor](/~amoor), 21.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-lange-sicht-nach-wahlen?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "NygP19bEI-",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Die Wahl­resultate in sechs Schweizer­karten

## 

#### Wo haben die Parteien verloren, in welchen Wähler­schichten haben sie gewonnen, wer war in den Städten vorne, wer auf dem Land? Die Wahl­analyse auf der Ebene der zweitausend Schweizer Gemeinden.

Von [Simon Schmid](/~simonschmid), 21.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-historischer-linksrutsch?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "GxPuGZRIOq",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Historischer Linksrutsch

## 

#### Die Klimapolitik ist die Forderung der Stunde. Aber diese Wahlen bringen vor allem eine Wende nach links.

Ein Kommentar von [Daniel Binswanger](/~dbinswanger), 21.10.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#fff",
      "author": "Von <a title='Andrea Arežina' href='/~aarezina'>Andrea Arežina</a>, <a title='Elia Blülle' href='/~eblulle' >Elia Blülle</a>, <a title='Dennis Bühler' href='/~dbuehler'>Dennis Bühler</a>, <a title='Anja Conzett' href='/~acon'>Anja Conzett</a>, <a title='Bettina Hamilton-Irvine' href='/~bhamilton.irvine'>Bettina Hamilton-Irvine</a>, <a title='Daniel Ryser' href='/~dryser'>Daniel Ryser</a> (Text) und Goran Basic (Bilder), 21.10.2019",
      "url": "",
      "title": "Grünsonntag",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/magazine/images/324ae6404339bbe2da42752f3a374cfe6babea05.jpeg",
      "lead": "Reportage über einen Wahltag der Superlative.",
      "bgColor": "#000"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-injektion-europa?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "rRMpXAdhB",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Was ist unsere beste Chance? Richtig: Die EU

## 

#### Letzte Worte vor der Wahl: Durch die Wahlwoche mit der Republik-Redaktion (I).

Ein Kommentar von [Simon Schmid](/~simonschmid), 14.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-gleichstellung?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "1HtZ1qktPq",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Liebe Schweiz: Es ist Zeit für 50 Prozent Frauen im Parlament

## 

#### Durch die Wahlwoche mit der Republik-Redaktion (IV).

Ein Kommentar von [Andrea Arežina](/~aarezina "Andrea Arežina") und [Bettina Hamilton-Irvine](/~bhamilton.irvine), 17.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-schweiz-wir-muessen-reden?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "nHnQzLse_Y",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Schweiz, du hast ein Demokratie­problem

## 

#### Durch die Wahlwoche mit der Republik-Redaktion (V).

Ein Kommentar von [Carlos Hanimann](/~chanimann), 18.10.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#000",
      "author": "Von <a href='/~robeck'>Ronja Beck</a> (Text) und Xaviera Altena (Illustration), 11.10.2019",
      "url": "https://www.republik.ch/2019/10/11/die-jungen-gehen-zu-wenig-waehlen-und-influencer-so",
      "title": "Die Jungen gehen zu wenig wählen. Und Influencer so: ¯\\_(ツ)_/¯",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/magazine/images/c72e2ea26581b6828e012ed8161ebf1cd5528650.gif",
      "lead": "Werden junge Schweizerinnen gefragt, was sie politisch motivieren würde, antworten viele: Influencer. Warum hat die Branche Angst vor der eigenen Macht?",
      "bgColor": "#F9E537"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-geht-waehlen-sonst-tun-es-andere?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "xLEDHSddk",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Ihr wollt Wähler? Gebt ihnen Party!

## 

#### In der Schweiz werden Wahlen behandelt wie der Geburtstag einer ungeliebten Grosstante. Es geht auch anders.

Ein Kommentar von [Elia Blülle](/~93d6839d-fe3e-491a-bbca-477585e776e4), 11.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-bern-wappet-sich-gegen-den-angriff-aus-dem-silicon-valley?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "7C_alNbyoe",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Die Schweiz wappnet sich für den Angriff aus dem Silicon Valley

## 

#### Recherchen zeigen: Facebooks «I’m a Voter»-Button hat Wahlen und Abstimmungen in 66 Ländern beeinflusst. Jetzt plant der Konzern, das umstrittene Instrument auch bei den eidgenössischen Wahlen einzusetzen. Bern ist alarmiert.

Von [Adrienne Fichter](/~adriennefichter), 16.05.2018

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-stimmrechtsalter-16?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "NX3j9pfVXg",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Mehr junge Wählende würden Zürich guttun

## 

#### Die Jugend interessiert sich wieder für Politik. Und trotzdem zeichnet sich bei den Zürcher Wahlen eine rekordtiefe Beteiligung ab. Was tun?

Von [Claude Longchamp](/~clongchamp "Claude  Longchamp"), 18.03.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#000",
      "author": "Von <a title='Elia Blülle' href='/~eblulle'>Elia Blülle</a>, <a title='Dennis Bühler' href='/~dbuehler'>Dennis Bühler</a>, <a title='Anja Conzett' href='/~acon'>Anja Conzett</a> (Text) und Reto Sterchi (Bilder), 21.09.2019",
      "url": "https://www.republik.ch/2019/09/21/methode-martullo",
      "title": "Methode Martullo",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/magazine/images/87c38f1874e7127122c6a0b1ebcae1fa518bf926.jpeg",
      "lead": "Sie gehört zum innersten Zirkel der SVP, ist eine mächtige Unternehmerin, reicher als alle anderen Parlamentarier zusammen. Ihr Wahlkampf? Ein Lehrstück in Menschenfängerei. Wer ist Magdalena Martullo?",
      "bgColor": "#F9F99C"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": false,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-wahlen-mobilisierung?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "wkO-BtIZm",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Was in der Schweiz Wahlen entscheidet

## 

#### Wer glaubt, dass Parteien einander Wähler abjagen, kennt nur einen Teil der Wahrheit. Das Zauberwort für den Erfolg lautet: Mobilisierung. Unsere Vorschau zu den Wahlen im Oktober.

Von [Claude Longchamp](/~clongchamp "Claude Longchamp"), 16.09.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-parlamentarierkarrieren?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "opClmY_XQ",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Mehr Stress im Ringen um politische Macht

## 

#### Wer wird wiedergewählt? Wer abgewählt? Im Herbst sind Wahlen. Wir analysieren, warum Schweizer Politiker aus dem Parlament ausscheiden – mit Daten der letzten 100 Jahre.

Von [Claude Longchamp](/~clongchamp "Claude  Longchamp"), 15.07.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-staenderatswahlen?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "YP8qo7jsfX",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Die stabile Kammer

## 

#### Bei den nationalen Wahlen bahnt sich ein Links-Grün-Rutsch an. Aber nur im Nationalrat. In der kleinen Kammer stehen die Zeichen anders. Ein Rück- und ein Ausblick zu den Ständeratswahlen.

Von [Claude Longchamp](/~clongchamp "Claude  Longchamp"), 20.05.2019

<hr /></section>

<hr /></section>

<hr /></section>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-parolen-quiz?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "ebBHLYDsD",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Welche Partei sind Sie, wenn Sie Partei sind?

## 

#### Sie sagen dem Fragetool, wie Sie bei den Abstimmungs­vorlagen der letzten vier Jahre entschieden haben. Das Tool sagt Ihnen, welcher Partei Sie am nächsten sind.

Von [Elia Blülle](<>), [Pascal Scheiwiler](/~f0d2dc2a-1308-4c40-b4ff-ca4e32f48019 "Pascal Scheiwiler") (Redaktion), [Andreas Moor](/~amoor) (Umsetzung) und Niels Blaesi (Illustrationen), 27.09.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-klimapolitik?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "p-BJ0l9LEC",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Die grosse Abrechnung

## 

#### Die Wahlen stehen an, die Legislatur ist zu Ende. Was hat die Bundes­versammlung in den vergangenen vier Jahren erreicht? Bei welchen Themen ist das Parlament gescheitert, und welche Herausforderungen stehen an? Der Rück- und Ausblick.

Von der Republik-Redaktion, 27.09.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-kantone-stimmverhalten?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "9exfFiqYke",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Auf lange Sicht

# Swissminiatur der Volks­abstimmungen

## 

#### Zürich und Bern setzen den Trend – und der Aargau wurde als Durchschnittskanton von Baselland und Graubünden abgelöst: eine politologische Analyse der ablaufenden Legislatur.

Von [Claude Longchamp](/~clongchamp "Claude Longchamp"), 17.06.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#fff",
      "author": "Von <a title='Sylke Gruhnwald' href='/~sylke'>Sylke Gruhnwald</a>, <a href='/~tpreusse'>Thomas Preusse</a> und <a title='Patrick Venetz' href='/~pae'>Patrick Venetz</a>, 13.09.2019</p>",
      "header": "Aus der Redaktion",
      "url": "https://www.republik.ch/2019/09/13/wahltindaer-erklaerung",
      "title": "Wählerin sucht Kandidat: Spielen Sie «Wahltindär»",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/magazine/images/5c967281d2b0527a382f6316f89975290c67f45c.png",
      "lead": "Über 4600 Personen kandidieren für den National- und Ständerat. Wofür stehen sie, welche Interessen vertreten sie? Wischen Sie, wie bei einer Dating-App, durch die Profile der Kandidatinnen in Ihrem Kanton.",
      "bgColor": "#670404"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": false,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-stell-dir-vor?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "qPOAsnQ-u",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Stell dir vor, du wirst in den Nationalrat gewählt ….

## 

#### …für wen setzt du dich ein und was ist es dir wert? Auftakt zum Lobbying-Schwerpunkt.

Von [Philipp Albrecht](/~palbrecht), [Dennis Bühler](/~dbuehler "Dennis Bühler") (Text) und Kati Rickenbach (Illustrationen), 02.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-man-kann-sich-grandios-irren?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "IoLfomu9JH",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# «Es gibt heute einfach zu viele Exzesse»

## 

#### Die Gesundheitsbranche und die Bauern haben eine Übermacht im Parlament, sagt der ehemalige Migros-Chef­lobbyist Martin Schläpfer. Ein Gespräch über die Kunst des Lobbyierens und die Folgen für die Politik.

Ein Interview von [Philipp Albrecht](/~palbrecht), [Dennis Bühler](/~dbuehler "Dennis Bühler") (Text) und Yves Bachmann (Bilder), 07.10.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-parteispenden?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "n9_1s0dvFV",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Wahlkampf-Millionen auf Bestellung

## 

#### Dokumente aus dem Innersten der SVP geben einen umfassenden Einblick in die Wahl­kampf­finanzierung der Partei. Wir haben sie analysiert – und veröffentlichen sie.

Von [Carlos Hanimann](/~chanimann) (Text) und Adam Higton (Illustration), 05.07.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>

<section><h6>DYNAMIC_COMPONENT</h6>

```
{
  "autoHtml": false,
  "props": {
    "item": {
      "color": "#fff",
      "author": "Von <a title='Daniel Ryser' href='/~dryser'>Daniel Ryser</a>, Olivier Würgler (Text) und Doug Chayka (Illustration), 06.06.2019",
      "url": "https://www.republik.ch/2019/06/06/homestory",
      "title": "Homestory",
      "split": true,
      "image": "https://cdn.repub.ch/s3/republik-assets/github/republik/article-wahnsinn-wahlkampf/images/c98623a67ed25b949a23f33115e9f359309bb337.gif",
      "lead": "Zwei seriöse Republik-Reporter touren kreuz und quer durch die Schweiz und suchen Politikerinnen und Politiker heim. Sie wollen die Demokratie retten … obwohl, nein, eigentlich wollen sie sich vor allem betrinken und dass die Politiker sie nicht mit Floskeln langweilen. Das ist «Homestory» – die Wahljahr-Serie.",
      "bgColor": "#000"
    }
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/banner.js?v2.9"
}
```

<hr /></section>

<section><h6>CENTER</h6>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": false,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-cvpfail?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-binswanger?autoSlug",
  "titleSize": "standard",
  "id": "RZ041pWub",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Warum stoppt Google die fragwürdige CVP-Kampagne nicht?

## 

#### Die brave Mittepartei fährt im Wahlkampf einen aggressiven Werbefeldzug im Internet. Die Kritik folgt prompt. Kaum hinterfragt wird dagegen die Rolle des Suchmaschinen­konzerns. Bis jetzt.

Von [Adrienne Fichter](/~adriennefichter), 19.09.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-interview-pfister?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "BXEyRUoDNo",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# «Die CVP muss zu einer Bewegung werden»

## 

#### Gerhard Pfister will von der SVP lernen und lehnt deren Stil ab. Der CVP-Chef über die Herausforderungen einer Mittepartei.

Ein Interview von [Urs Bruderer](/~ubruderer) und [Dennis Bühler](/~dbuehler "Dennis Bühler"), 28.03.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-cvp?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "I5TE-AVhyN",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Im Reich der Mitte

## 

#### Die CVP will das Land zusammenhalten – und sich so vor dem Zerfall retten. Kann das klappen? Eine Reise durch Stammlande und Parteigeschichte.

Von [Urs Bruderer](/~ubruderer), 27.03.2019

<hr /></section>

<hr /></section>

<hr /></section>

<section><h6>ARTICLECOLLECTION</h6>

```
{
  "membersOnly": true,
  "unauthorizedText": ""
}
```

## 

<section><h6>TEASERGROUP</h6>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-chancenloses-chancenland?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-binswanger?autoSlug",
  "titleSize": "standard",
  "id": "BbXpwQtMN",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Binswanger

# Chancenloses Chancen­land

## 

#### Die Operation Libero unterstützt mit einer überparteilichen Kampagne Nationalrats­kandidatinnen aus verschiedenen Lagern. Doch Überparteilichkeit ist ein dehnbarer Begriff.

Von [Daniel Binswanger](/~dbinswanger), 07.09.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-der-hitzesommer-waehlt-mit?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-binswanger?autoSlug",
  "titleSize": "standard",
  "id": "jq1zx0wiWc",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Binswanger

# Der Hitzesommer wählt mit

## 

#### Im Moment versuchen die Bürgerinnen, sich abzukühlen, im Herbst werden sie wählen. Was viel miteinander zu tun hat.

Von [Daniel Binswanger](/~dbinswanger), 29.06.2019

<hr /></section>

<section><h6>TEASER</h6>

```
{
  "reverse": false,
  "color": "#000",
  "teaserType": "articleTile",
  "byline": null,
  "onlyImage": false,
  "url": "https://github.com/republik/article-tb?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "titleSize": "standard",
  "id": "MHYzeAy53C",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Im Zweifels­fall geschmeidig

## 

#### Thierry Burkart vertritt in der FDP alte Werte und gilt als frische Kraft. Der Aargauer ist auf bestem Weg in den Ständerat.

Ein Porträt von Ursula von Arx (Text) und Yves Bachmann (Bilder), 19.07.2019

<hr /></section>

<hr /></section>

<hr /></section>



<hr /></section>
