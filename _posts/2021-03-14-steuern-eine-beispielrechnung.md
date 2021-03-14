---
layout: post
title: Steuern in der GmbH?
comments: true
---


Wie bei <a href="https://f.hubspotusercontent00.net/hubfs/8060256/Steuersatze-privat-vs-GmbH.pdf">Ride</a> beschrieben ist ein Vorteil der GmbH, 
  dass niedrigere Steuern auf Gewinne fällig sind. Aber wie wird das nun berechnet? 
 <p>Bei der Privatperson ist die Sache einfach. Für 10.000 Euro Gewinn aus Dividenden oder Aktienverkäufen werden 801 Euro Freibetrag (sofern noch nicht ausgeschöpft)
 abgezogen und der Rest mit Abgeltungssteuer, Soli und ggf. Kirchensteuer belegt (Beispielrechnung ohne Kirchensteuer):

{% highlight js %}
(10.000-801)*0.73625= 6772,77
{% endhighlight %}

Für die Privatperson bleiben von 10.000 Euro Gewinn also 6772 Euro.</p>
Die niedrigeren Steuern in der GmbH, wie z.B. 1.54%, auf Aktien sind effektive Steuern, d.h. auf diesen Steuersatz gelangt man am Ende der Rechnung.
Hat eine GmbH zum Beispiel folgende Zahlen im Jahr:

* Aktiengewinne: 6.000 Euro
* Optionsgewinne: 4.000 Euro 
* Betriebskosten: 3.000 Euro

Damit ergibt sich als Rechnung für den zu versteuerenden Jahresgewinn:

{% highlight js %}
(6.000*0.05)+4.000-3.000=1.300
{% endhighlight %}

Aktiengewinne werden, wegen der Teilfreistellung, nur zu 5% eingerechnet. Für Optionsgeschäfte gilt keine Teilfreistellung, also werden diese voll eingerechnet.
Auf die verbleibenden 1.300 Euro werden ca. 30% Steuern (Gewerbesteuer, Körperschaftsteuer erhoben, also ergibt sich eine Steuerlast von 390 Euro.
Das heißt von den 10.000 Euro Gewinn verbleiben der GmbH, nach Steuern und Betriebskosten, 6.610 Euro:

{% highlight js %}
10.000-3.000-390=6.610
{% endhighlight %}

In dem Fall ist die GmbH also im Vergleich zur Privatperson schlechter dran.
Das lässt sich nun ändern indem man mehr Ausgaben in die GmbH verschiebt oder andere Vorteile wie die unbegrenzte Verlustverrechnung bei Optionsgeschäften nutzt. Zudem sind die Betriebskosten in der reinen Trading GmbH relativ konstant, egal ob 10.000 Euro, 20.000 Euro oder 30.000 Euro Gewinn erzielt werden.
