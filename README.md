# Wenn Pristina plötzlich wichtiger ist als London: Am Flughafen Zürich wirbelt Corona die Bedeutung der Destinationen durcheinander
Die Coronapandemie hat zu kaum für möglich gehaltenen Einbrüchen im Flugverkehr geführt. Was bleibt davon? Was ist temporär? Und was machen die Betroffenen wie Flughafenbetreiber und Fluggesellschaften? Eine Datenanalyse am Beispiel des Flughafens Zürich mit besonderer Betrachtung der Fluggesellschaft Swiss.

## Ausgangsthese
Der durch die Coronapandemie ausgelöste Einbruch beim Flugverkehr ist anders als frühere Einbrüche. Er wird zu grundlegenden Veränderungen in der Flugbranche führen. Einerseits, weil er zu einer Zeit kommt, in der die ökologischen Auswirkungen des Fliegens verstärkt diskutiert werden (Stichwort: Flugscham). Andererseits, weil er Unternehmen aufzeigt, was durch moderne Technik möglich ist (Stichwort: Videokonferenzen).

## Ursprungsidee
Mit Anfang der Coronapandemie sind ab März 2020 sowohl private als auch geschäftliche Flugreisen eingebrochen. Der Flugverkehr kam beinahe zum Stillstand, der Branchendachverband IATA sprach von einem Schock historischen Ausmasses. Im Sommer 2020 konnte sich der Flugverkehr nur leicht erholen, blieb dann insbesondere im folgenden Winter weiter sehr tief. Mit den wärmeren Monaten 2021 schien sich eine weitere Erholung anzubahnen.

Vom vor-pandemischen Zustand war die Flugbranche aber noch immer weit entfernt. Doch dieser Einbruch könnte, so meine Ausgangsthese, ohnehin anders als frühere Einbrüche (z.B. 9/11 und Swissair-Grounding im sogenannten Katastrophenherbst 2001) nicht vollständig kompensiert werden. Schon vor der Pandemie machten Begriffe wie Flugscham die Runde und (Nacht-)Zugverbindungen wurden ausgebaut. Mit der Pandemie erfuhren zudem viele Firmen, dass eben doch vieles auch per Videokonferenz erledigt werden kann. Auch wenn Flugreisen wieder problemlos möglich sein werden, wird ein Teil der Passagiere im Vergleich zu vor Corona fehlen.

Diese Entwicklung möchte ich mit Daten zum Flugverkehr untersuchen. Zwei Jahre nach Beginn der Pandemie (Stichtag: Erster Coronafall in der Schweiz am 25. Februar 2020) möchte ich einen aktuellen Stand zeigen und danach in regelmässigen Abständen eine Aktualisierung liefern (quartalsweise). Ich fokussiere dabei auf den Flughafen Zürich und lege zudem ein besonderes Augenmerk auf die Schweizer Fluggesellschaft Swiss als grösste nationale Airline und wichtigste Airline am Standort Zürich.

**Mission Statement:**
Ich möchte, dass mein Publikum...
* ...zwei Jahre nach Pandemiebeginn den Stand des Flugverkehrs am Beispiel Flughafen Zürich kennt und die Entwicklung für alle Ziele selber durchsuchen kann.
* ...danach quartalsweise in einer aktualisierten Version nachschauen kann, wie die Entwicklung fortgeschritten ist.

## Anpassung an These und Idee
Es zeigte sich schnell, dass die Daten zum Flugverkehr nicht zeitnah verfügbar sind. Zwar sind von einigen Anbietern Jahreszahlen bis und mit 2021 zu beziehen, aber einerseits fehlen auch diesen rund zwei Monate bis zum Stichtag Ende Februar und andererseits sind die aussagekräftigsten Zahlen vom Bundesamt für Statistik zu erhalten, diese allerdings vorerst nur bis und mit drittes Quartal 2021. Die Zahlen bis Ende Jahr folgen voraussichtlich im März 2022, die Zahlen bis mindestens zum Stichtag Ende Februar (genauer: bis Ende erstes Quartal 2022) gar erst im Sommer.

Entsprechend musste ich den Plan, den Stand zwei Jahre nach Pandemiebeginn zu zeigen, fallenlassen. Die Auswertungen werden mit dem maximal verfügbaren Zeitraum vorgenommen. Wo möglich werden Datensätze kombiniert. Um dann die geplante Betrachtung zum zweiten Jahrestag doch noch machen zu können, wird ein noch grösserer Fokus darauf gelegt, den Programmcode so zu gestalten, dass mit aktuellen Datensätzen sofort neue Auswertungen ohne Anpassungen am Code möglich sind.

## Einschätzung von Aufwand und Ertrag
Ich schätze den Aufwand für die Beschaffung der Daten und vor allem das erstmalige Programmieren als relativ hoch ein. Die veranschlagten fünf Tage dürften kaum ausreichen. Weil die erstellten Notebooks aber regelmässig wieder verwendet werden können, ist der Ertrag auch entsprechend hoch und der Aufwand rechnet sich von Aktualisierung zu Aktualisierung mehr. In Anbetracht dessen, dass die Coronapandemie weiterhin andauert und die Auswirkungen uns noch lange beschäftigen werden, erscheint der Aufwand als gerechtfertigt.

## Knackpunkte
1. Verfügbarkeit der Daten: Die Daten müssen nicht nur möglichst zeitnahe vorliegen, sondern auch genug detailliert sein, dass Aussagen zu Veränderungen getroffen werden können (eine reine Passagieranzahl ohne Destinationen würde das kaum ermöglichen).
2. Entwicklung der Coronapandemie: Neue Virusvarianten, geänderte Reisebestimmungen und vieles mehr. Corona ist unberechenbar, entsprechend kann die Entwicklung des Flugverkehrs auch immer wieder beeinflusst werden.
3. Grafik: Während Passagierzahlenentwicklungen mit Datawrapper und/oder Flourish erstellt werden können, sind Netzwerkkarten für die Verbindungen ab Zürich schwieriger zu erstellen. Vermutlich ist hier die Hilfe des CH-Media-Infografik-Teams nötig.

## Briefingpersonen
Ich habe mich einerseits mit meinem Team bei CH Media ausgetauscht. Hier ging es vor allem um Fragen des Storytellings. Wir definierten, dass die Grundstruktur des Artikels bei der Entwicklung der Flugpassagierzahlen ansetzen sollte. Zwar ist der Einbruch weitgehend bekannt, aber er gehört dennoch zum kompletten Bild und dient zusammen mit einem leicht szenischen Einstieg in die Zeit zu Beginn der Pandemie als guter Eye-Catcher. Danach soll der Blick aber schnell auf neue Erkenntnisse gelegt werden und insbesondere Veränderungen bezüglich der ab Zürich angeflogenen Destinationen zeigen.

Andererseits habe ich mich mit Benjamin Denes unterhalten. Er ist heute Geschäftsführer bei der Electronic Media School (EMS) und war zuvor mehrere Jahre beim Spiegel tätig. Er war unter anderem Gründer von Planestream und produziert den Podcast Flugforensik. Er hat insbesondere mit Hinweisen auf mögliche Datensätze und Quellen geholfen.

Schliesslich habe ich mich auch mit dem CH-Media-Infografik-Team bezüglich optischer Umsetzung ausgetauscht. Die Erstellung einer Netzwerkkarte wurde als grundsätzlich möglich erachtet.

## Datensätze/Quellen
Zur Verwendung kamen (siehe auch [Arbeitsprotokoll, KW38-44](#kw38-44-20-september-bis-7-november-2021)):
* Bundesamt für Statistik: [Flugpassagiere im Linien- und Charterverkehr (Monatszahlen seit 2000)](https://www.pxweb.bfs.admin.ch/pxweb/de/px-x-1107020000_102/px-x-1107020000_102/px-x-1107020000_102.px)
* Bundesamt für Statistik: [Flugbewegungen (Starts und Landungen) im Linien- und Charterverkehr (Monatsdaten seit 2000)](https://www.pxweb.bfs.admin.ch/pxweb/de/px-x-1107020000_101/px-x-1107020000_101/px-x-1107020000_101.px)
* Bundesamt für Statistik: [Flugpassagiere pro Destination (auf Anfrage zugestellt)](destinationen/wmove_wvs_2018_2021__kunde.xlsx)
* OAG: [Angebotene Sitze und Flüge ab Zürich pro Fluggesellschaft (auf Anfrage zugestellt)](OAG/ZRH_Data.xlsx)
* Flughafen Zürich: [provisorische Zahlen Oktober - Dezember 2021 aus Medienmitteilungen](https://www.flughafen-zuerich.ch/newsroom/?h=1&t=Medienmitteilung)

## Code
Die entstandenen Jupyter Notebooks sind in den jeweiligen Schritten im Arbeitsprotokoll erwähnt. Zusammengefasst sind das:
* [Flugpassagiere ab ZRH pro Monat seit 2000](passagiere/Flugpassagiere_ab_ZRH_pro_Monat_seit_2000.ipynb)
* [Flugbewegungen ab ZRH pro Monat seit 2000](passagiere/Flugbewegungen_ab_ZRH_pro_Monat_seit_2000.ipynb) (nicht verwendet)
* [Destinationen der Passagiere ab ZRH pro Monat seit 2018](destinationen/Destinationen.ipynb)
* [Sitze und Flüge pro ab Zürich angeflogenem Flughafen](OAG/OAG.ipynb) (kaum verwendet, weil Städte statt Flughafen sinnvoller)
* [Sitze und Flüge pro ab Zürich angeflogener Stadt](OAG/OAG-Städte.ipynb)
* [Sitze und Flüge pro ab Zürich angeflogener Stadt pro Airline und mit Fokus auf die Swiss](OAG/OAG-Airlines.ipynb)

## Arbeitsprotokoll
*Im folgenden werden wochenweise Fortschritte und Entwicklungen dokumentiert. Wenn in einer Kalenderwoche nichts geschehen ist, werden Wochen auch zusammengefasst. Die Erkenntnisse aus Gesprächen und Datenanalysen werden nur ansatzweise hier wiedergegeben. Sie sind detaillierter im Artikel und den verlinkten Jupyter-Notebooks zu finden.*

#### KW35 (30. August bis 5. September 2021)
Idee schärfen für Besprechung im CAS-Bootcamp in der Folgewoche

#### KW36-37 (6. bis 19. September 2021)
CAS-Bootcamp mit Vorstellung der Ideen und Verarbeitung des Feedbacks

#### KW38-44 (20. September bis 7. November 2021)
Gelegentliches Suchen nach möglichen Datensätzen. Grundsätzlich weiterzuverfolgen:
* Bundesamt für Statistik, Direktabfrage Stat-Tab: [Flugpassagiere im Linien- und Charterverkehr (Monatszahlen seit 2000)](https://www.pxweb.bfs.admin.ch/pxweb/de/px-x-1107020000_102/px-x-1107020000_102/px-x-1107020000_102.px)
* Bundesamt für Statistik, Direktabfrage Stat-Tab: [Flugbewegungen (Starts und Landungen) im Linien- und Charterverkehr (Monatsdaten seit 2000)](https://www.pxweb.bfs.admin.ch/pxweb/de/px-x-1107020000_101/px-x-1107020000_101/px-x-1107020000_101.px)
* Bundesamt für Statistik, Excel-Dateien: [Quartalszahlen inkl. Passagiere nach Endziel/Streckenziel (Tabellenblätter B2 und C2)](https://www.bfs.admin.ch/bfs/de/home/aktuell/neue-veroeffentlichungen.assetdetail.19144823.html)
* OAG: [Auf Anfrage](http://www.oag.com)
* Flightradar24: [Auf Anfrage](http://www.flightradar24.com)
* Skyguide: [Auf Anfrage](http://www.skyguide.ch)

Zurückgestellt, weil nicht auf den ersten Blick nützlich und/oder kostenpflichtig und/oder kein Zugriff:
* [Aviationstack](http://www.aviationstack.com)
* [Flightstats](http://www.flightstats.com)
* [Routes online](http://www.routesonline.com)
* [Expertflyer](http://www.expertflyer.com)
* [Flightaware](http://www.flightaware.com)
* [Radarbox](http://www.radarbox.com)

#### KW45 (8. bis 14. November 2021)
Erste Auswertungen der Zahlen des Bundesamts für Statistik: Die Anbindung an die Stat-Tab-API klappt noch nicht. Die ersten Auswertungen erfolgen mit dort erstellten und anschliessend abgespeicherten CSV-Dateien. **Erste Erkenntnisse: Einbruch der Passagierzahlen lässt sich mit den BfS-Daten derzeit bis und mit September 2021 abbilden)**

#### KW46 (15. bis 21. November 2021)
Die Anbindung an die Stat-Tab-API klappt nun. Die Anzahl Flugpassagiere pro Monat erfolgt nun direkt im Jupyter Notebook [Flugpassagiere ab ZRH pro Monat seit 2000](passagiere/Flugpassagiere ab ZRH pro Monat seit 2000.ipynb) und bildet immer den aktuellsten Stand ab (aktuell: September 2021). In den Daten des Bundesamts für Statistik scheint ein Fehler vorzuliegen. Im Juli 2008 ist der Wert viel zu hoch (rund 5,5 Millionen Passagiere statt rund 2 Millionen Passagiere in Zürich). Das BfS bestätigt das auf Nachfrage und verspricht, den Fehler auszumerzen. Zudem frage ich beim BfS an, ob die in den Excel-Dateien enthaltenen Daten mit den Destinationen der Passagiere auch monatsweise erhältlich ist. Gleichzeitig erstelle ich auch das Jupyter Notebook [Flugbewegungen ab ZRH pro Monat seit 2000](passagiere\Flugbewegungen ab ZRH pro Monat seit 2000.ipynb), das aber nicht sicher zum Einsatz kommt (die Entwicklung dürfte im Wesentlichen ähnlich sein wie jene der Passagiere).

#### KW47 (22. bis 28. November 2021)
Das BfS hat den Fehler im Juli 2008 korrigiert. Zudem hat das BfS eine Auswertung der ab Zürich abfliegenden Passagiere mit Destination pro Monat für den Zeitraum 2018 bis 2020 als CSV-Datei zugestellt. Erste Auswertungen mit diesem finden im Jupyter Notebook [Destinationen](destinationen/Destinationen.ipynb") statt. Dabei fällt auf: Beim BfS muss beim Export ein Fehler geschehen sein. Es scheint, als ob jeweils im ersten Monat alle Flüge pro Destination zusammengefasst wurden, die Passagierzahlen gar nur für diesen ersten Monat vorliegen. Beim BfS bitte ich um Korrektur und zudem um eine Auswertung bis und mit mindestens September 2021 (gleicher Stand wie im Stat-Tab bei den reinen Passagierzahlen).

#### KW48-49 (29. November bis 12. Dezember 2021)
Flightradar antwortet auf eine erneut Anfrage zum Stand der Datenbeschaffung, dass es bald soweit sein sollte. Skyguide liefert Zahlen, die aber nicht mehr als die reinen Flugbewegungen hergeben (wäre auch über Stat-Tab abrufbar), das verfolge ich nicht weiter. Das BfS liefert eine bereinigte Version der Passagierzahlen pro Destination. Allerdings weiterhin nur bis Ende 2020. Und nur bis auf Länder runtergebrochen. Ich frage erneut beim BfS nach. 

#### KW50-1 (13. Dezember 2021 bis 9. Januar 2022)
Das BfS hat nun eine Datei geliefert, die brauchbar ist, wenn auch erst bis Ende 2020 Zahlen aufweist. Ich achte beim Code darauf, dass eine neue Lieferung vom BfS zu keinen Anpassungen führen muss. **Erste Erkenntnisse: London ist die wichtigste Destination zu normalen Zeiten. Mit der Pandemie werden in einzelnen Monaten andere Ziele wichtiger. Auffällig: Pristina wird gegen Ende 2020 am wichtigsten.**

#### KW2-3 (10. bis 23. Januar 2022)
Das BfS hat nun die Datei bis Ende drittes Quartal 2021 ergänzt. Nun sind konkrete Auswertungen möglich. **Weitere Erkenntnisse: Pristina ist in weiteren Monaten eine wichtige Destination, neu tauchen auch Istanbul und Palma de Mallorca auf. Es scheint sich zu zeigen, dass sich Urlaubsreisen schneller erholen als Geschäftsreisen.** Gleichzeitig fange ich mit dem Erstellen des Artikels an. Dabei ergänze ich die Flugpassagierzahlen ab Zürich, die über Stat-Tab nur bis September 2021 reichen, mit provisorischen Zahlen, die ich direkt von der Webseite des [Flughafens Zürich](https://www.flughafen-zuerich.ch/newsroom/?h=1&t=Medienmitteilung) beziehe. Ich habe mich gegen einen Einbezug dieser Zahlen in das Jupyter Notebook entschieden, weil dort die Zahlen des Flughafen Zürichs für Oktober bis Dezember 2021 irrelevant werden, sobald die Daten des BfS (Stat-Tab) aktualisiert wurden.

#### KW4 (24. bis 30. Januar 2022)
OAG hat Daten geliefert, die für die jeweils ganzen Jahre von 2017 bis 2021 angeben, wie viele Sitze von welcher Fluggesellschaft zu welcher Destination angeboten wurden und wie viele Flüge die Airline zu diesen Destinationen durchgeführt hat. Der Datensatz ermöglicht einige zusätzliche Auswertungen. Im Jupyter Notebook [OAG](OAG/OAG.ipynb) mache ich Auswertungen zu den angeflogenen Flughäfen. Weil im Datensatz des BfS die Destinationen nur nach Ort, nicht nach Flughafen unterschieden werden, baue ich die OAG-Daten im Notebook [OAG-Städte](OAG/OAG-Städte.ipynb) um. **Erste Erkenntnisse: Das Bild wiederholt sich: Unter anderem Palma de Mallorca und Pristina werden zu wichtigen Destinationen.** Von Flightradar sind weiterhin keine Daten eingetroffen, diesen Datensatz schreibe ich ab.

#### KW5 (31. Januar bis 6. Februar 2022)
Bei der Analyse der OAG-Daten zeigt sich, dass Istanbul ebenfalls wichtiger wird. Das führt im Folgenden zur Erkenntnis, dass auch die Turkish Airlines an Bedeutung für den Flughafen Zürich gewinnt. Ich entscheide mich deshalb, zum einen Artikel einen zweiten mit einem Fokus auf die Airlines zu stellen. Die Auswertungen dafür geschehen im Notebook [OAG-Airlines](OAG/OAG-Airlines.ipynb). Beide Artikel werden in der Folge zu etwa drei Vierteln fertiggestellt.

#### KW6 (7. bis 13. Februar 2022)
Die abgeschlossenen Auswertungen lasse ich mir durch Experten und Betroffene einordnen. Die Erkenntnisse aus den Gesprächen mit dem Flughafen Zürich, einem Aviatik-Experten der Universität St.Gallen und der Swiss fliessen in die beiden Artikel ein. Die beiden Artikel stelle ich in der Folge fertig. Zudem erstellt mir die CH-Media-Infografik zwei Grafiken, die ich nicht mit den üblichen Tools selber erstellen konnte. Aus der einen Grafik entsteht zudem das Teaserbild.
 
## Ergebnis
Entstanden sind zwei Artikel:
* [Wenn Pristina plötzlich wichtiger ist als London: Am Flughafen Zürich wirbelt Corona die Bedeutung der Destinationen durcheinander](http://www.tagblatt.ch/ld.2245284)
* [Corona stärkt den Ferienflugverkehr, davon profitiert Edelweiss mehr als Swiss](http://www.tagblatt.ch/ld.2247051)

Beide Artikel wurden am 12. Februar 2022 veröffentlicht und gegenseitig verlinkt. Artikel 1 wurde zuerst ins Schaufenster gestellt (Top-Bereich verschiedener CH-Media-Plattformen sowie Push-Mitteilung und Posts in Sozialen Medien), Artikel 2 folgt einige Tage später.

## Ansätze für weitere Auswertungen und Artikel
Die Aktualisierung der Flugpassagierzahlen lässt sich mit wenig Aufwand betreiben, sobald neue Zahlen in Stat-Tab hinterlegt sind. Für die Auswertung der Destinationen und/oder der Bedeutung der Airlines ist ein erneuter Datenbezug beim BfS oder bei OAG nötig. Kommen die Daten von dort aber in der gleichen Form, ist auch hier kaum Anpassungsbedarf vorhanden.

Die Auswertung könnte in weiten Teilen für andere Schweizer Flughäfen wiederholt werden. Passagierzahlen könnten über Stat-Tab mit wenig Anpassungsbedarf für alle Schweizer Flughäfen bezogen werden. Bei der Auswertung der Destinationen und der Bedeutung der Airlines ist hingegen eine Datenlieferung des BfS und von OAG nötig.

Reizvoll könnte ein Vergleich mit dem Angebot an und der Nutzung von Nachtzugverbindung aus der Schweiz in europäische Grossstädte sein, die auch per Flugzeug erreichbar sind.