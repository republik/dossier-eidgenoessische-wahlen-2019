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

Letzte Aktualisierung: 03.10.2019

<hr /></section>

<section><h6>CENTER</h6>

Die Schweiz wählt alle vier Jahre ein neues Parlament. Dieses Jahr kandidieren 4 663 Personen für alle 200 Sitze im Nationalrat; 183 Kandidatinnen bewerben sich für 45 Sitze im Ständerat (Appenzell Innerrhoden wählte bereits im April [Daniel Fässler](https://www.parlament.ch/de/biografie/daniel-fässler/4056) von der CVP).

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
        "description": "Anzahl Kandidierende für 245 Sitze in National- und Ständerat",
        "source": {
          "name": "Republik Wahltindär",
          "url": "https://www.republik.ch/wahltindaer",
          "date": "01.10.2019"
        },
        "color": "#39bbcc"
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
        "color": "#39bbcc"
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
        "color": "#39bbcc"
      },
      {
        "type": "timer",
        "label": "Countdown",
        "value": 1571652000000,
        "description": "Zeit bis zur Schliessung der meisten Wahllokale am 21. Oktober um 12:00",
        "color": "#39bbcc"
      }
    ]
  },
  "src": "https://cdn.republik.space/s3/republik-assets/dynamic-components/dossier/indicators.js?v2.9",
  "size": "breakout"
}
```

<hr /></section>

Lorem ipsum dolor. Etwas zum Nationalrat…

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
    "#ff7f0e",
    "#BCBD21",
    "#2077B4",
    "#FFDD00",
    "#2BA02B",
    "#bbb"
  ]
}
```

### Fragmentierung der Mitte

Stimmenanteile der Parteien bei Nationalratswahlen

```
year,party,value
1999,GPS,0.049664
1999,SP,0.224735
1999,CVP,0.158537
1999,GLP,0.000000
1999,FDP,0.199171
1999,BDP,0.000000
1999,SVP,0.225438
1999,Übrige,0.142455
2003,GPS,0.074324
2003,SP,0.233227
2003,CVP,0.143750
2003,GLP,0.000000
2003,FDP,0.173347
2003,BDP,0.000000
2003,SVP,0.266532
2003,Übrige,0.108820
2007,GPS,0.095861
2007,SP,0.195462
2007,CVP,0.144789
2007,GLP,0.014272
2007,FDP,0.157614
2007,BDP,0.000000
2007,SVP,0.288968
2007,Übrige,0.103034
2011,GPS,0.084328
2011,SP,0.187222
2011,CVP,0.123040
2011,GLP,0.053809
2011,FDP,0.151045
2011,BDP,0.054154
2011,SVP,0.265562
2011,Übrige,0.080839
2015,GPS,0.070571
2015,SP,0.188410
2015,CVP,0.116459
2015,GLP,0.046259
2015,FDP,0.163967
2015,BDP,0.041038
2015,SVP,0.293860
2015,Übrige,0.079438
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen.assetdetail.217191.html).

<hr /></section>

Lorem ipsum solor. Etwas zum Ständerat…

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

Lorem ipsum. Etwas zum Wahlverhalten…

<section><h6>CHART</h6>

```
{
  "type": "TimeBar",
  "y": "value",
  "unit": "%",
  "numerFormat": "%",
  "xTicks": [
    "1935",
    "1951",
    "1967",
    "1983",
    "1999",
    "2015"
  ],
  "domain": [
    0,
    100
  ],
  "xIntervalStep": 4,
  "colorRange": [
    "#39bbcc"
  ]
}
```

### Einpendeln oder Trendwende?

Wahlbeteiligung bei Nationalratswahlen seit 1935

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
```

Quelle: [BFS](https://www.bfs.admin.ch/bfs/de/home/statistiken/politik/wahlen/nationalratswahlen/wahlbeteiligung.assetdetail.217210.html).

<hr /></section>

Lorem ipsum dolor. Etwas zum Abschluss…

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
  "unauthorizedText": "",
  "membersOnly": false
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
  "id": "wkO-BtIZm",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### 

# Stell dir vor, du wirst in den Nationalrat gewählt und musst nun Interessen vertreten. Für wen setzt du dich ein und was ist es dir wert?

## 

#### Auftakt zum Lobbying-Schwerpunkt.

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
  "url": "https://github.com/republik/article-koeppel-hat-recht?autoSlug",
  "kind": "opinion",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-binswanger?autoSlug",
  "titleSize": "standard",
  "id": "opClmY_XQ",
  "portrait": true,
  "showImage": true,
  "bgColor": "#fff"
}
```

###### Binswanger

# Köppel hat recht

## 

#### Im Ständeratswahlkampf ist Roger Köppel chancenlos, deshalb denunziert er die Konkurrenten als «Pöstli-Jäger». Das Manöver ist zwar peinlich und durchschaubar, aber der Vorwurf nicht unberechtigt.

Von [Daniel Binswanger](/~dbinswanger), 28.09.2019

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
  "id": "YP8qo7jsfX",
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
      "header": "Aus der Redaktion",
      "author": "Von <a title='Sylke Gruhnwald' href='/~sylke'>Sylke Gruhnwald</a>, <a href='/~tpreusse'>Thomas Preusse</a> und <a title='Patrick Venetz' href='/~pae'>Patrick Venetz</a>, 13.09.2019</p>",
      "url": "https://www.republik.ch/2019/09/13/wahltindaer-erklaerung",
      "title": "Wählerin sucht Kandidat: Spielen Sie unser «Wahltindär»",
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
  "unauthorizedText": "",
  "membersOnly": false
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
  "id": "qPOAsnQ-u",
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
  "formatColor": "#08809A",
  "onlyImage": false,
  "url": "https://github.com/republik/article-wahlen-mobilisierung?autoSlug",
  "kind": "editorial",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-auf-langer-sicht?autoSlug",
  "titleSize": "standard",
  "id": "IoLfomu9JH",
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
  "url": "https://github.com/republik/article-chancenloses-chancenland?autoSlug",
  "kind": "opinion",
  "center": false,
  "textPosition": "topleft",
  "formatUrl": "https://github.com/republik/format-binswanger?autoSlug",
  "titleSize": "standard",
  "id": "n9_1s0dvFV",
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
  "unauthorizedText": "",
  "membersOnly": false
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
  "url": "https://github.com/republik/article-opa-wird-schwierig?autoSlug",
  "kind": "opinion",
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

###### Binswanger

# Opa wird schwierig

## 

#### Bei der SVP ist der Wurm drin. Doch Roger Köppel hat ein Rezept, um die Situation zu retten: mit Feingefühl.

Von [Daniel Binswanger](/~dbinswanger), 24.08.2019

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
  "id": "BXEyRUoDNo",
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



<hr /></section>
