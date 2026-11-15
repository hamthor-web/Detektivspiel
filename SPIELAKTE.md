# Detektivspiel – zentrale Spielakte und Vereinbarungen

**Stand:** 15.11.2026 · **Status:** Konzept in Entwicklung, erster eigenständiger HTML-Prototyp vorhanden, aber noch keine freigegebene Endfassung.

> **Verbindlicher Ablageort für dieses Spiel:** Dieses Repository `hamthor-web/Detektivspiel`. Hier werden künftig alle bestätigten Entscheidungen und der technische Stand dokumentiert. Eine Datei in GitHub ist **nicht automatisch** eine ChatGPT-Projektquelle. Änderungen an der bestehenden App `hamthor-web/lesedetektive` sind damit **nicht** erfolgt.

## 1. Bestätigte Entscheidungen

- **Ein einziges zusammenhängendes Detektivspiel**, keine vier oder fünf eigenständigen Minispiele. Ein Fall umfasst mehrere abwechslungsreiche Ermittlungsrunden.
- Die **Detektivakte** enthält die Aufgabe, Hinweise und den Ermittlungsfortschritt. Neue Fälle kommen nach und nach hinzu.
- Das Kind kann **eine zufällige Fallakte ziehen** oder **einen bestimmten Fall selbst auswählen**.
- Jeder Fall erhält einen **bezeichnenden, neugierig machenden Namen**, etwa **„Wer stahl des Schneemanns Nase?“**. Das Wortspiel *stahl/Stahl* ist als Materialidee ausdrücklich willkommen.
- Nach erfolgreicher Aufklärung wird die Akte als **„GELÖST“ gekennzeichnet und sichtbar an eine Pinnwand geheftet**. Die Pinnwand ist die wachsende Sammlung abgeschlossener Fälle.
- Ausgangspunkt sind die ähnlichen Wörter aus der von Heike bereitgestellten Sammlung **„Nur ein bisschen anders“**. Weitere passende Wörter dürfen frei ergänzt werden.
- **Buchstabenveränderungen und Spurensuche** sollen zum Spielkern gehören. Die Hinweise müssen innerhalb der Geschichte **sinnvoll und notwendig** sein; Wortpaare dürfen nicht bloß künstlich aneinandergereiht werden.
- **Reißwolf-Idee:** Ein Wort oder eine Nachricht verschwindet oben in einem Aktenvernichter; unten purzeln **einzelne bunte, durcheinandergewürfelte Buchstaben** heraus. Die genaue Spielmechanik ist noch offen.
- **Glücksrad-Idee:** Das Glücksrad soll als mögliches Ermittlungswerkzeug berücksichtigt werden; seine konkrete Funktion ist **noch nicht beschlossen**.
- Die Entwicklung erfolgt **zunächst nur im neuen Repository** `hamthor-web/Detektivspiel`. Das bestehende Repository `hamthor-web/lesedetektive` bleibt bis zu einer ausdrücklichen Integrationsentscheidung unverändert.

## 2. Offen und nicht beschlossen

- Konkreter Ablauf der einzelnen Fälle, Zahl der Runden pro Fall, Schwierigkeitsstufen und Hinweise.
- Ob und wie Glücksrad und Reißwolf zusammenwirken; ob es falsche/echt bleibende Spuren und verschiedene Ermittlungswege gibt.
- Ob Zufall zunächst ungelöste Fälle bevorzugt und wie bereits gelöste Fälle erneut spielbar sind.
- Wie das Detektivbüro, die Akten und die Pinnwand bildlich und animiert gestaltet werden.
- Ob die Spielfigur ein Buchstabendieb ist und welche Rolle mögliche Verdächtige spielen.
- Der erste Fall **„Die verschwundene Nase“** ist ein **Prototyp**. Insbesondere der Übergang **MAUS → HAUS** wurde als erzählerisch unlogisch beanstandet. Die Geschichte ist zu überarbeiten, bevor sie als Fall freigegeben wird.
- Anzahl und Reihenfolge der künftigen Fälle sowie Veröffentlichung als eigenständiges Spiel oder spätere Einbindung in die Lesedetektive.

## 3. Bereits existierende Materialien / technische Abgrenzung

- Materialquelle: hochgeladenes Dokument **„Nur ein bisschen anders“**, 57 ähnliche Wortpaare (redaktionell noch nicht vollständig auf Eignung und Korrektheit geprüft).
- Im Chat wurde die eigenständige HTML-Testdatei **`Lesedetektive_Fall_01_Die_verschwundene_Nase.html`** bereitgestellt sowie ein erster Fallakten-Nachtrag. **Das ist kein Beleg für eine GitHub-Veröffentlichung.**
- Dieses Repository wurde von Heike am 15.11.2026 neu angelegt, damit das Experiment nicht die bereits funktionierenden Lesedetektive verändert.
- Technische Funktionen, Animationen, Spielstände oder Geräteprüfungen werden **nur dann als umgesetzt** geführt, wenn die zugehörigen Dateien tatsächlich im Repository beziehungsweise im Test vorliegen.

## 4. Gestaltungsregeln für die spätere Umsetzung

- Zielgruppe: Kinder der 2. Klasse, auch Deutsch als Zweitsprache; Lesen und Verstehen stehen im Mittelpunkt.
- Sinnvolle Nutzung der Bildschirmfläche, große Schriften und Buttons mit ausreichendem Kontrast.
- Hoch- und Querformat sowie Smartphone und Tablet berücksichtigen; Inhalte dürfen auch mit vergrößerter Schrift nicht abgeschnitten werden.
- **Zwei voneinander unabhängige Zoomfunktionen:** Spielfeld/Bilder und Schrift.
- Dekorierte Schaltflächen nicht verzerren; Randbereiche proportional erhalten, nur neutrale Mittelflächen anpassen.
- Kinder sollen ohne unnötigen Zeitdruck ermitteln können. Falls später Zeitrunden eingeführt werden, muss die aktive Zeit bei Unterbrechung korrekt pausieren.
- Vor Freigabe Test auf unterschiedlichen Bildschirmgrößen, insbesondere Hoch-/Querformat und beide Zoomregler.

## 5. Vereinbarung zur Projektverwaltung und Speicherorten

1. **GitHub:** Diese Spielakte ist ab jetzt die fortlaufend zu pflegende **zentrale Fassung** der Entscheidungen für das Detektivspiel. Code und ausführbare Fassungen liegen gesondert im selben Repository. Jede technische Änderung muss gegen den tatsächlichen GitHub-Stand geprüft werden.
2. **ChatGPT-Projektquellen:** Dateien landen dort **nicht automatisch**, nur weil sie im Chat erstellt, als Download angeboten oder auf GitHub gespeichert wurden. Der Status der Aufnahme als Projektquelle muss jeweils ausdrücklich geprüft oder als offen gekennzeichnet werden.
3. **Chats:** Die Gespräche sind Entwicklungs- und Entscheidungsverlauf, aber **kein Ersatz** für die gepflegte Spielakte.
4. **Masterübersicht der Lesespiele:** Beim nächsten Abgleich der zentralen Projektverwaltung ist ein eigenständiger Eintrag „Detektivspiel – in Planung/Prototyp“ mit Link auf dieses Repository vorzusehen. **Nicht als bereits aktualisiert ausgeben**, bevor das wirklich geschehen ist.
5. Keine vorhandenen Chats, Quellen, Repositories, Dateien oder bestätigten Animationen ohne ausdrückliche Zustimmung löschen, verschieben oder überschreiben.
6. Jede größere Änderung mit Datum, Status (**beschlossen / vorgeschlagen / programmiert / getestet / veröffentlicht**) und bei Bedarf Link auf Commit oder Test dokumentieren.

## 6. Nächster sachlicher Schritt

Den ersten Fall erzählerisch neu konstruieren, sodass jedes Wort-Rätsel **aus einem konkreten Hinweis entsteht**. Reißwolf und Glücksrad als echte, unterscheidbare Ermittlungswerkzeuge testen, ohne die Lesedetektive-App zu verändern.
