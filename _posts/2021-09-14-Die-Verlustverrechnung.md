---
layout: post
title: Die Verlustverrechnung
comments: true
---

Es war schon mehrfach Thema, dass eine GmbH sinnvoll ist, wenn man Optionen handelt, um die Verlustbegrenzung auf 20.000 EUR zu umgehen.
Aber was bedeutet das in der Praxis? Wie schnell kommen solche Summen zusammen? Intuitiv denkt man sich, dass 20.000 EUR eine Menge Geld sind.
Bei Optionen gibt es aber verschiedene Strategien in denen das Verkaufen und das Kaufen von Optionen kombiniert wird, das nennt sich zum Beispiel Spread.
Damit hat man einen definiertes Risiko, weil die Verluste der einen Option durch die Gewinne der anderen Option ausgeglichen werden. Im Umkehrschluß bedeutet das aber auch, dass hier Verluste einkalkuliert sind.

In der letzten Earnings Seasons habe ich verschiedene Optionen gehandelt, unter anderem auch einen Butterfly auf Zoom. 
Bei einem Butterfly kauft man 2 Put Optionen und verkauft 2 Put Optionen, dafür erhält man ingesamt eine Gutschrift. Solche Kombinationen kann man sich zum Beispiel 
auf  <a href="https://optionstrat.com/build/long-put-butterfly/ZM/211015P190,211015P220x-2,211015P250">optionstrat</a> berechnen lassen. 

Die Quartalszahlen von Zoom wurden am 30.08.21 bekannt gegeben, ich habe am 30.08.21 einen Butterfly mit folgenden Komponenten für ca. 100 EUR Credit gemacht:

* + 1x 03SEP21 310.0 P
* - 2x 03SEP21 320.0 P
* + 1x 03SEP21 325.0 P

Nach Bekanntgabe der Ergebnisse ist Zoom allerdings völlig abgestürzt und zwar von fast 350$ auf 290$, wie man schön in den Tageskerzen sieht:

![_config.yml]({{ site.baseurl }}/images/20210914-zm-chart.png)

Damit waren alle Puts im Geld also auch meine beiden verkauften Puts. Hätte ich jetzt nur einen reinen Short Put gemacht, hätte ich ordentlich Verlust eingefahren, durch
die beiden Long Puts wurde das aber abgefedert. Nachdem ich den Trade geschlossen habe, sah das Ergebnis so aus:

![_config.yml]({{ site.baseurl }}/images/20210914-zm-result.png)

Am Ende habe ich mit den beiden Short Puts also 4.455,36 EUR verloren und mit den Long Puts 4.046,53 EUR gewonnen, also ingesamt nur einen Verlust von 408.83 EUR gemacht.
Nun kommt die Verlustbegrenzung ins Spiel: Wenn man davon ausgeht, dass die Privatperson nur noch 20.000 EUR Verlust aus Optionen ansetzen darf, dann ist der Verlusttopf nach 4-5 relativ simplen Trades voll!
Die GmbH tradet hingegen einfach fröhlich weiter.

PS:
Insgesamt liefen die Earnings dennoch gut, Zoom war der einzige Ausreißer.

