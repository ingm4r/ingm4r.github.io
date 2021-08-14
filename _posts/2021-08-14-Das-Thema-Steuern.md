---
layout: post
title: Das Thema Steuern
comments: true
---

Weil von vielen Seiten immer wieder das Thema Steuern angesprochen wird, möchte ich dazu nochmal einen kurzen Post machen.
Generell sollte man sich bewusst sein, dass die GmbH Gewinne mit ca. 30% versteuern muss. Für Aktien und ETFs ist die Belastung geringer weil hier es hier Teilfreistellungen gibt, wodurch nicht 100% der Gewinne für die Versteuerung zugrunde gelegt werden. Bei Dividenden, Optionsgewinnen oder Gewinnen aus Krypto gibt es sowas nicht. Von daher sollte es natürlich das Ziel der GmbH sein immer möglichst steueroptimal zu handeln und im Idealfall also nur Aktiengewinne zu erzielen, da diese am niedrigsten besteuert werden. Nun habe ich allerdings Aktien (AAPL, MSFT, VIRT und XOM) die Dividende ausschütten (Erklärung zum Aktienportfolio <a href="https://www.reddit.com/r/hebelwerk/comments/nxnnz1/der_yolohamaetf/">hier</a>. 


Im letzten Post habe ich bereits erwähnt, dass die GmbH ihre Fixkosten aus den Bruttogewinnen decken kann, also vereinfacht gesagt: "Betriebseinnahmen - Betriebsausgaben = Gewinn".

Natürlich können nicht beliebige Kosten als Betriebsausgaben angesetzt werden, dazu gibt es ausführliche <a href="https://www.lexware.de/wissen/buchhaltung-finanzen/betriebsausgaben/">Übersichten</a>. Diesen lässt sich entnehmen, dass beispielweise Kosten für den Steuerberater, IHK und Kreditzinsen abziehbar sind.

Was heißt das jetzt am konkreten Beispiel?
Für die GmbH setze ich jährliche Betriebskosten von ca. 3.000 EUR an. Nehmen wir an aus den Aktien erhält die GmbH jährlich eine Dividende in Höhe von 4.500 EUR.
Damit ergibt sich also eine steuerliche Belastung von:

{% highlight js %}
4500-3000 = 1500
1500 * 0.3 = 450
{% endhighlight %}

Die GmbH zahlt also, nach Abzug der Betriebskosten, auf den verbleibenden Gewinn von 1500 EUR Steuern in Höhe von 450 EUR.
Optimal wäre es natürlich nicht 4500 EUR Gewinn aus Dividenden zu erzeugen sondern diese durch Aktienerlöse (95% Teilfreistellung) zu haben.
Aber auch gemischte Ansätze funktionieren, zum Beispiel 3.000 EUR Gewinn aus Dividenden und 1.500 EUR aus Aktienverkäufen.
Durch die Teilfreistellung der Aktiengewinne wären von den 1.500 EUR Aktiengewinnen nur 75 EUR zu versteuern. Die Rechnung wäre also:

{% highlight js %}
1500*0.05 = 75
3000+75=3075
3075-3000 = 75
75 * 0.3 = 22,5
{% endhighlight %}

Und in dem gemischten Ansatz verbleibt eine Steuerlast von 22.5 EUR für die GmbH.

Für die GmbH sollte man also die Betriebskosten als "umgekehrten Freibetrag" sehen, in dem Sinne, dass man diese Summe mit Dividenden und Optionsgewinne quasi "steuerfrei" erwirtschaften kann. Alles was darüber hinaus geht, sollte dann idealerweise durch Aktiengewinne entstehen. Das bedeutet auch beim Optionshandel empfiehlt es sich immer steueroptimiert zu denken. Ein einfaches Beispiel ist hier ein Long Call der im Plus ist, anstelle diesen gewinnbringend zu verkaufen, ist sinnvoller diesen auszüben und anschließend die zugeteilten Aktien zu verkaufen.

Leider gibt es im deutschen Finanzuniversum relativ wenige Personen die sich ausführlich mit Optionsstrategien beschäftigen. Im <a href="https://www.reddit.com/r/hebelwerk/">Hebelwerk subreddit</a> entsteht gerade eine Community zu diesem Thema. Wer sich dafür interessiert sollte dort, bzw. im <a href="https://discord.gg/hebelwerk">Discord</a> vorbeigucken. 

