# Wenn Palma de Mallorca plötzlich wichtiger wird als London – Veränderungen im Flugverkehr ab Zürich während und wegen der Coronapandemie
Die Coronapandemie hat zu kaum für möglich gehaltenen Einbrüchen im Flugverkehr geführt. Was bleibt davon? Was ist temporär? Und was machen die Betroffenen wie Flughäfen und Fluggesellschaften? Eine Datenanalyse am Beispiel des Flughafens Zürich mit besonderer Betrachtung der Fluggesellschaft Swiss.

## Ausgangsthese
Der durch die Coronapandemie ausgelöste Einbruch beim Flugverkehr ist anders als frühere Einbrüche. Er wird zu grundlegenden Veränderungen in der Flugbranche führen.

## Ursprungsidee
Mit Anfang der Coronapandemie sind ab März 2020 sowohl private als auch geschäftliche Flugreisen eingebrochen. Der Flugverkehr kam beinahe zum Stillstand, der Branchendachverband IATA sprach von einem Schock historischen Ausmasses. Im Sommer 2020 konnte sich der Flugverkehr nur leicht erholen, blieb dann insbesondere im folgenden Winter weiter sehr tief. Mit den wärmeren Monaten 2021 schien sich eine weitere Erholung anzubahnen.

Vom vor-pandemischen Zustand war die Flugbranche aber noch immer weit entfernt. Doch dieser Einbruch könnte, so meine Ausgangsthese, ohnehin anders als frühere Einbrüche (z.B. 9/11 und Swissair-Grounding im sogenannten Katastrophenherbst 2001) nicht vollständig kompensiert werden. Schon vor der Pandemie machten Begriffe wie Flugscham die Runde und (Nacht-)Zugverbindungen wurden ausgebaut. Mit der Pandemie erfuhren zudem viele Firmen, dass eben doch vieles auch per Videokonferenz erledigt werden kann. Auch wenn Flugreisen wieder problemlos möglich sein werden, wird ein Teil der Passagiere im Vergleich zu vor Corona fehlen.

Diese Entwicklung möchte ich mit Daten zum Flugverkehr untersuchen. Zwei Jahre nach Beginn der Pandemie (Stichtag: Erster Coronafall in der Schweiz am 25. Februar 2020) möchte ich einen aktuellen Stand zeigen und danach in regelmässigen Abständen eine Aktualisierung liefern (quartalsweise). Ich fokussiere dabei auf den Flughafen Zürich und lege zudem ein besonderes Augenmerk auf die Schweizer Fluggesellschaft Swiss als grösste nationale Airline und wichtigste Airline am Standort Zürich.

**Mission Statement:**
Ich möchte, dass mein Publikum...
* ...zwei Jahre nach Pandemiebeginn den Stand des Flugverkehrs am Beispiel Flughafen Zürich kennt und die Entwicklung für alle Ziele selber durchsuchen kann.
* ...danach quartalsweise in einer aktualisierten Version nachschauen kann, wie die Entwicklung fortgeschritten ist.

## Anpassung an These und Idee
*siehe dazu auch Arbeitsprotokoll (Datum)*
Es zeigte sich schnell, dass die Daten zum Flugverkehr nicht zeitnah verfügbar sind. Zwar sind von einigen Anbietern Jahreszahlen bis und mit 2021 zu beziehen, aber einerseits fehlen auch diesen rund zwei Monate bis zum Stichtag Ende Februar und andererseits sind die aussagekräftigsten Zahlen vom Bundesamt für Statistik zu erhalten, diese allerdings vorerst nur bis und mit drittes Quartal 2021. Die Zahlen bis Ende Jahr folgen voraussichtlich im März 2022, die Zahlen bis mindestens zum Stichtag Ende Februar (genauer: bis Ende erstes Quartal 2022) gar erst im Sommer.

Entsprechend musste ich den Plan, den Stand zwei Jahre nach Pandemiebeginn zu zeigen, fallenlassen. Die Auswertungen werden mit dem maximal verfügbaren Zeitraum vorgenommen. Wo möglich werden Datensätze kombiniert. Um dann die geplante Betrachtung zum zweiten Jahrestag doch noch machen zu können, wird ein noch grösserer Fokus darauf gelegt, den Programmcode so zu gestalten, dass mit aktuellen Datensätzen sofort neue Auswertungen möglich sind.

## Einschätzung von Aufwand und Ertrag

## Knackpunkte

## Briefingpersonen

## Datensätze/Quellen

## Code

## Arbeitsprotokoll
#### KW35 (30. August bis 5. September 2021)
Idee schärfen für Besprechung im CAS-Bootcamp in der Folgewoche

#### KW36-37 (6. bis 19. September 2021)
CAS-Bootcamp mit Vorstellung der Ideen und Verarbeitung des Feedbacks

### KW38-44 (20. September bis 7. November 2021)
Gelegentliches Suchen nach möglichen Datensätzen und ähnlichen Arbeiten/Artikeln.

###

| Datum | Tätigkeit |
| -------- | ---- | ------------- |
| 02.09.2021 | Idee schärfen für Besprechung im CAS-Bootcamp |
| 17.09.2021 | Feedback aus CAS-Bootcamp verarbeiten |
| 18.11.2021 | Erste Analysen der Daten des Bundesamts für Statistik |


	- Anzahl Passagiere, die über Zürich reisen: Python-Script fertig, direkte Anbindung an Stat-Tab, aktualisierbar
		○ Anzahl Passagiere Linienverkehr und Charterverkehr pro Monat 2000 bis September 2021 (Tabelle und Plot)
		○ Veränderungen zu Vormonat/Vorjahr
		○ Veränderungen aller Monate ab 2020 (Pandemie) zum korrespondierenden Monat 2019 (vor Pandemie)
	- Anzahl Flugbewegungen in Zürich: Python-Script fertig, direkte Anbindung an Stat-Tab, aktualisierbar
		○ Anzahl Flüge Linienverkehr und Charterverkehr pro Monat seit 2000 bis September 2021 (Tabelle und Plot)
		○ Veränderungen zu Vormonat/Vorjahr
		○ Veränderungen aller Monate ab 2020 (Pandemie) zum korrespondierenden Monat 2019 (vor Pandemie) 
	- Anzahl Passagiere nach Zieldestination, abfliegend ab Zürich: Python-Script fertig, keine direkte Anbindung (Excel-Datei vom BfS), theoretisch aktualisierbar (ob neu Excel-Dateien gleich daherkommen, ist aber unsicher, das erste Update kam gleich daher)
		○ Anzahl Passagiere pro Monat nach Zieldestination 2018 - Q3 2021
		○ Relative Bedeutung der Zieldestination
		○ Veränderungen der Anzahl Passagiere je Destination (absolut und relativ)
	- Anzahl angebotener Sitze und durchgeführter Flüge mit OAG-Daten
	- Grundstruktur Artikel 1 fertig
Grundstruktur Artikel 2 fertig


		○ BfS-Probleme
		○ BfS-Fehler
		○ Ausgangsthese und Wieterentwicklung
		○ Fehlende BfS-Daten mit Flughafen-Daten ergänzt
		○ OAG-Daten ermöglichen auch die Sicht auf die vertretenen Fluggesellschaften und das konkrete Streckennetz (nicht nur Orte)
		○ Flugbewegungen (BfS) dann nicht verwendet, weil die Kurve im Wesentlichen das Gleiche zeigt wie die Flugpassagiere-Ansicht. Zudem, wenn Bewegungen angeschaut werden sollen, können wir das auch mit den OAG-Daten machen, die noch genauer sind (Flughafen statt nur Ort)
		○ Zielland und Kontinent entfernt (wenn ich damit noch was machen muss, macht eine Betrachtung mit Fokus darauf eh mehr Sinn als die bei den Orten immer mitzunehmen)
		○ Endziele ebenfalls entfernt
		○ OAG-Daten pro Flughafen zwar analysiert, aber zwecks Vergleichbarkeit eher auf Städte schauen (zweites Notebook); sonst in London mehrere Flughäfen (z.B.); und ansonsten müsste man z .B. bei Berlin den Flughafenwechsel noch beachten.
Hoher Fokus auf Automatisierung, weil die BfS-Zahlen regelmässig kommen


 
## Ergebnis

## Ansätze für weitere Auswertungen und Artikel
Alle Schweizer Flughäfen
Nachtzugverbindungen im Vergleich