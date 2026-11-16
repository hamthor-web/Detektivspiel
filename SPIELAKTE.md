# Detektivspiel – zentrale Spielakte

**Stand:** 15.11.2026 · **Status:** Konzeptentwicklung.  
**Repository:** https://github.com/hamthor-web/Detektivspiel  
**Spätere mögliche Integration:** viertes Spiel der Lesedetektive, nur nach gesonderter Freigabe.

> Diese Datei ist die verbindliche, fortlaufende Dokumentation des Spielkonzepts. Sie unterscheidet ausdrücklich Beschlüsse, Ideen und technische Umsetzung. GitHub-Dateien werden nicht automatisch zu ChatGPT-Projektquellen.

## Ziel und Material

Ein zusammenhängendes Detektivspiel für Kinder der zweiten Klasse (auch DaZ) über ähnlich geschriebene Wörter und die Bedeutung kleiner Buchstabenänderungen. Ausgangsmaterial: Nutzerdatei **„nur ein bisschen anders .docx“** mit 57 Wortpaaren und Beispielsätzen. Die Nutzerin hat weitere passende Wörter ausdrücklich erlaubt. Wörter sollen nicht willkürlich umgewandelt werden: **Die Geschichte muss das Worträtsel notwendig machen**. Es soll eine echte Spurensuche mit Schlussfolgerung entstehen, keine bloße Folge isolierter Richtig/Falsch-Aufgaben.

## Bestätigte Entscheidungen

1. **Ein einziges Spiel** mit verschiedenen Detektivfällen und abwechslungsreichen Ermittlungsrunden; keine getrennten Minispiele.
2. **Fallakten mit bezeichnenden Titeln** und laufend erweiterbarem Bestand. Nutzerbeispiel: **„Wer stahl des Schneemanns Nase?“** einschließlich des Wortspiels *stahl/Stahl*.
3. **Fallwahl:** Das Kind kann entweder eine **Zufallsakte** erhalten oder eine Akte **selbst auswählen**.
4. **Mehrere zusammenhängende Schritte** pro Fall; Hinweise sammeln und am Ende den Fall wirklich aufklären.
5. **Pinnwand:** Eine abgeschlossene Akte wird als **„GELÖST“** markiert und mit einer auffälligen Bewegung an die Pinnwand **geknallt/geheftet**. So werden erledigte Fälle sichtbar gesammelt.
6. **Eigenständige Entwicklung:** Nur das neue Repository `hamthor-web/Detektivspiel` verwenden. Die bestehende App im Repository `hamthor-web/lesedetektive` nicht ungefragt verändern. Spätere Integration ausdrücklich entscheiden.
7. **Eine zentrale GitHub-Spielakte:** Bestätigte Beschlüsse und größere Arbeitsschritte hier festhalten; keine parallelen unübersichtlichen Nachtragsketten. Nichts Bestehendes ohne Zustimmung löschen, verschieben oder überschreiben.

## Ausdrücklich eingebrachte Ideen, Details noch offen

- **Veränderte Buchstaben:** ähnliche Wörter / Austausch, Ergänzung oder Wegfall von Buchstaben als Ermittlungsmechanik. Das Kind soll die Lösung oft aus dem Handlungskontext erschließen und nicht immer vorgegeben bekommen.
- **Glücksrad:** Nutzeridee, könnte Ermittlungsaufgaben oder Hinweise auswählen. **Genaue Funktion nicht beschlossen.** Zufall darf den logischen Zusammenhang des Falls nicht zerstören.
- **Reißwolf:** Nutzeridee: Oben verschwindet ein Wort oder Schriftstück, unten fallen **einzelne bunte, durcheinandergewürfelte Buchstaben** heraus. Mögliche Rekonstruktion von Hinweiswörtern; genaue Aufgabe noch offen.
- **Detektivbüro** als Startoberfläche mit Akten, Pinnwand, Glücksrad, Reißwolf; Gestaltungsvorschlag, kein fertig bestätigtes Layout.
- Persönliche Pinnwand und dauerhafte Speicherung je Kind, erneutes Spielen gelöster Fälle, bevorzugt ungelöste Zufallsakten: plausible Vorschläge; konkrete Speichervorgaben noch festzulegen.

## Mögliche Ermittlungsrunden (Ideen, nicht final beschlossen)

- Manipulierten Buchstaben in einem Hinweis finden.
- Fehlenden Buchstaben / Buchstabengruppe aus einem Satz erschließen.
- Bunten Buchstabensalat aus dem Reißwolf rekonstruieren.
- Verdächtige befragen, Aussagen vergleichen, echte und falsche Spuren unterscheiden.
- Glücksrad für abwechslungsreiche, aber logisch passende Spuren einsetzen.
- Hinweise kombinieren und eine echte Schlussfrage beantworten.
- Verschieden lange Fälle mit verschiedenen Aufgabentypen.

## Erster Testfall: noch kein freigegebener Handlungsentwurf

Arbeitstitel **„Die verschwundene Nase“**, später vielleicht **„Wer stahl des Schneemanns Nase?“**.

Eine eigenständige HTML-Datei `Lesedetektive_Fall_01_Die_verschwundene_Nase.html` wurde im Chat erstellt. Testfolge: **HASE → NASE**, **MAUS → HAUS**, **FISCH → TISCH**, **TASSE → TASCHE**, danach Schlussauflösung.

**Kritik der Nutzerin:** MAUS → HAUS ist erzählerisch nicht überzeugend. Der Fall muss inhaltlich neu durchdacht werden, damit jedes Rätsel eine nachvollziehbare Spur ist. Der Prototyp ist **nicht freigegeben und noch nicht in dieses Repository hochgeladen**.

## Verbindliche Gestaltungsregeln

- Zielgruppe zweite Klasse: große, gut lesbare, kontrastreiche Schrift und gut erreichbare, große Schaltflächen.
- Verfügbare Bildschirmfläche sinnvoll nutzen; keine abgeschnittenen Inhalte.
- Smartphone/Tablet im Hoch- und Querformat.
- **Zwei unabhängige Zoomfunktionen** für Spielfeld/Bilder einerseits und Schrift andererseits.
- Dekorierte Buttonränder unverzerrt erhalten; nur neutrale Mitte dehnen.
- Vor Freigabe Geräteformate, Orientierungen und beide Zoomregler prüfen.
- Kein Zeitmodus beschlossen; zunächst ohne Zeitdruck.

## Technischer Stand (bei Anlage dieser Akte)

| Bestandteil | Tatsächlicher Stand |
|---|---|
| Eigenes GitHub-Repository | Neu eingerichtet |
| `SPIELAKTE.md` | Mit dieser Änderung angelegt |
| Erster Testfall | Nur als eigenständige HTML-Chatdatei, **nicht hier** |
| Glücksrad/Reißwolf | Ideen, **nicht implementiert** |
| Detektivbüro/Pinnwand | Konzept, **nicht implementiert** |
| Persönliche Fortschrittsspeicherung | Noch nicht implementiert |
| Weitere Fälle | Noch nicht entwickelt |
| Integration in „Lesedetektive“ | Nicht beauftragt |
| Tests einer fertigen Version dieses Repositories | Noch nicht möglich |

## Offene Entscheidungen und nächste Schritte

1. Den ersten Fall mit wirklich begründeten Hinweisen neu entwickeln.
2. Reißwolf und Glücksrad als unterschiedliche Aufgabenmechaniken konzipieren.
3. Unterschiedliche Ermittlungsrunden mit sinnvollem Fallabschluss erproben.
4. Fallwahl, Pinnwand und Fortschrittsspeicherung pro Kind im Detail klären.
5. Die Wortpaare redaktionell auf eindeutige Bedeutungen, richtige Schreibung und Altersangemessenheit prüfen.
6. Spielprototypen **im neuen Repository** testen; alte Lesedetektive nicht ungefragt verändern.

## Quellen, Versionen und Projektverwaltung

- **Diese Datei:** maßgebliche dokumentierte Entscheidungen und offener Entwicklungsstand.
- **GitHub-Code:** einzig maßgeblicher Nachweis tatsächlich hochgeladener Implementierungen.
- **Originalmaterial:** `nur ein bisschen anders .docx` aus dem Projektchat; noch nicht hier hinterlegt.
- **Alter erster HTML-Prototyp:** Datei im Chat, noch nicht hier hinterlegt.
- **Historische Entscheidungen:** Chatverlauf vom 15.11.2026.
- **ChatGPT-Projektquellen und Masterübersicht:** Werden durch GitHub **nicht automatisch** aktualisiert. Für das zentrale Projekt muss bei Statusänderungen separat eine Verknüpfung bzw. eine Übersicht gepflegt werden.

## Neue Konzeptidee: geheimes Glücksrad, Türen und mehrstufige Hinweise (15.11.2026)

**Status: ausdrücklich zur Spielakte hinzuzufügende Idee, aber noch kein final bestätigter Fallablauf.**

- Hinweise können **versteckt** sein und das Kind schrittweise zu einer **bestimmten Tür oder einem geheimen Raum** führen. Der Weg muss aus dem Lesen und Deuten von Spuren hervorgehen.
- Mögliche Rätselmechaniken auf diesem Weg: **ein überflüssiger Buchstabe**, ein **umgestelltes Wort / Anagramm**, ein fehlender Buchstabe oder eine verdächtige Wortveränderung. Welche Mechanik für welchen Fall sinnvoll ist, bleibt offen.
- **Erst nach einer erfolgreichen Spurensuche erscheint ein verborgenes Glücksrad** – zum Beispiel hinter einer Tür, einem beweglichen Bild oder einem Bücherregal. Das Kind entdeckt es, statt es bloß jederzeit im Hauptmenü aufzurufen.
- Das Rad **gibt einen wichtigen Buchstaben oder Wortteil aus**, der zunächst gesammelt und möglicherweise **erst später** zum Öffnen einer Kiste, Entschlüsseln einer Nachricht oder Auflösen des Falls gebraucht wird.
- Beispiel **nur zur Illustration**: Das Glücksrad liefert „S“; später findet sich „_CHLOSS“. Das Kind kombiniert den Hinweis und ergänzt „SCHLOSS“. Das ist noch keine geprüfte Geschichte.
- Das Rad sollte den für den Fall nötigen Hinweis **verlässlich liefern**. Der Dreh sorgt für Spannung, darf aber eine logisch notwendige Lösung nicht vom Glück abhängig machen.
- Das lässt sich später mit dem **Reißwolf** verbinden: Aus zerkleinerten Dokumenten fallen bunte, durcheinandergewürfelte Buchstaben, die mithilfe zuvor gesammelter Hinweise gedeutet werden.

### Wiederkehrende Hauptfigur / Markenzeichen – bestätigt

**Das bisherige Würstchen im gestreiften Pyjama mit Krönchen bleibt das wiedererkennbare Markenzeichen des Spiels**, wie in den anderen Lesespielen. Das Glücksrad ist lediglich ein verstecktes Ermittlungswerkzeug, **nicht** das Markenzeichen oder eine Ersatzfigur.

Für spätere Animationen gilt: Vorhandene Würstchen-Videos und die zuletzt freigegebene Bewegungsreferenz berücksichtigen; keine neue Ganganimation ohne ausdrückliche Freigabe. Die genaue Rolle des Würstchens im Detektivbüro, bei Rätseln und beim Fallabschluss ist noch zu gestalten.

## Fall 01 – neue Schneemann-Szene und Fortsetzung (16.11.2026)

**Status:** Eingangsszene als Nutzeridee aufgenommen; fortführender Fallablauf ist **ein Vorschlag**, nicht final freigegeben und nicht programmiert.

### Ursprungsidee der Nutzerin – ausdrücklich zu bewahren

Das **Würstchen im gestreiften Pyjama mit Krönchen** kommt an einem Schneemann vorbei. Mitten in dessen Gesicht steht ein **Topf Sahne**. Der Schneemann jammert: **„Hilfe! Hilfe! Mach, dass das weggeht!“** Das Würstchen erkennt, dass etwas falsch ist, kann das Fehlende aber zunächst nicht benennen. Es wirft die Sahne in einen **Mixer**. Heraus kommen die bunten Einzelbuchstaben **S, A, H, N, E**. Das Kind legt daraus **NASE**. Das **H** bleibt übrig, kommt in den **Rucksack** und wird **später im selben Fall benötigt**.

Das ist der neue entscheidende Ansatz: Eine ungewöhnliche Szene führt zu einer sinnvollen Leseaufgabe und erzeugt gleichzeitig einen **aufbewahrten Hinweis**. Die Nutzerin hat mit „Mixer“ ein konkretes Gerät genannt; der ältere Reißwolf bleibt eine mögliche zusätzliche Ermittlungsmechanik und darf nicht stillschweigend an dessen Stelle gesetzt werden.

### Ausformulierter Fallablauf – vorläufiger Ausbau

1. **Hilferuf im Schnee:** Würstchen trifft den Schneemann mit Sahnetopf statt Karottennase; die echte Nase ist verschwunden.
2. **Buchstabenmixer:** Aus SAHNE fallen S, A, H, N, E. Das Kind legt NASE; H wandert in den Rucksack. Die Lösung benennt das Fehlende, findet aber noch nicht die echte Karotte.
3. **Zettel im Garten:** „Suche bei der _UT!“ Der gespeicherte Buchstabe H ergibt **HUT**. Unter einem sichtbaren Hut liegt ein Schlüssel. Die Darstellung muss den richtigen Hut eindeutig auffindbar machen.
4. **Verstecktes Glücksrad:** Der Schlüssel öffnet eine Tür an einer Hütte. Dahinter wird ein verborgenes Glücksrad entdeckt. Es liefert einen für die nächste Spur benötigten Buchstaben **K**, der in den Rucksack wandert. Das Rad darf den zum Lösen notwendigen Buchstaben nicht zufällig vorenthalten.
5. **Zweiter Zettel:** „Die Antwort liegt in der _ISTE.“ Das Kind ergänzt das K zu **KISTE**, findet eine Kiste und öffnet sie.
6. **Beweis und Auflösung:** In der Kiste liegen Karotte und ein Brief. **Vorschlag:** Ein Hase hat die Karotte für einen Geburtstagskuchen genommen und Sahne als vermeintlichen Ersatz dagelassen. Das Kind beantwortet Fragen nach Täter, Grund und Sahne-Ersatz. **Diese Tätergeschichte ist nur ein erster Versuch und kann verändert werden.**
7. **Pinnwand-Abschluss:** Karottennase kehrt zurück; die Akte erhält einen Stempel **„FALL GELÖST!“** und wird mit einem kräftigen „KLACK!“ an die persönliche Pinnwand geheftet. Eine neue eigene Fallakte soll dort später hinzukommen können.

### Lernmechanik und Hinweise für die Umsetzung

- Mehrschrittige Spurensuche und **späteres Wiederverwenden** eines überzähligen Buchstabens; kein bloßes Aneinanderreihen isolierter Wortpaare.
- Wortzerlegung und Anagramm bei **SAHNE → NASE + H**; Buchstabenergänzung bei **_UT → HUT** und **_ISTE → KISTE**.
- Schrift klar sichtbar an der Maschine darstellen, damit die Umwandlung von Sahne in Buchstaben für das Kind verständlich bleibt.
- Vorläufig ohne Zeitdruck; Lese- und Animationspausen sollen vom Kind kontrollierbar sein.
- Großer Schriftregler und unabhängiger Bild-/Spielfeldzoom, gut bedienbar im Hoch- und Querformat.
- Rucksack-Inhalt in der laufenden Ermittlung erreichbar und nachvollziehbar; keine wichtigen Hinweise durch nicht reproduzierbaren Zufall verlieren.
- Nicht automatisch davon ausgehen, dass Fallgeschichte, Illustrationen oder Animationen bereits erstellt oder getestet sind.

**Detailkonzept:** [FALL_01_KONZEPT.md](FALL_01_KONZEPT.md).

## Ermittlungswerkzeug-Idee: Zitruspresse (16.11.2026)

**Status: Nutzeridee für das Werkzeugrepertoire zukünftiger Detektivfälle; nicht auf Fall 01 festgelegt, noch nicht programmiert.**

- Neben Buchstabenmixer, Reißwolf und geheimem Glücksrad soll eine **Zitruspresse** als mögliches Ermittlungswerkzeug vorgemerkt werden.
- Mit ihr kann das Kind aus einem rätselhaften Gegenstand, einer Frucht, einem Fundstück oder einer Nachricht **einen noch fehlenden Buchstaben „herauspressen“**. Was genau hineinkommt und weshalb der Buchstabe darin verborgen ist, muss sich aus der jeweiligen Fallhandlung ergeben.
- Der herausgepresste Buchstabe wird anschließend in einem Wort oder Hinweis eingesetzt beziehungsweise bis zur späteren Verwendung gesammelt.
- Die Zitruspresse soll **nicht automatisch in den Schneemann-Fall** eingebaut werden. Ihr Einsatz bleibt für geeignete spätere Fälle offen.
- Für die spätere Gestaltung denkbar: eine humorvolle Press-Animation, bei der statt Saft ein einzelner gut sichtbarer Buchstabe erscheint; diese Animation ist noch nicht beschlossen oder erstellt.

## Weitere Ermittlungswerkzeuge: Besen, Teppichklopfer, Fön und Strohhalm (16.11.2026)

**Status: Nutzerideen für das Werkzeugrepertoire späterer Fälle; noch nicht einzelnen Fällen zugeordnet und nicht programmiert.**

- **Besen:** Ein versteckter Buchstabe wird mit dem Besen **unter einem Möbelstück hervorgeholt**. Der Fund kann eine Lücke in einem Hinweis füllen.
- **Teppichklopfer:** Das Kind klopft einen staubigen Teppich aus; **im aufgewirbelten Staub erscheint der gesuchte Buchstabe**. Die Enthüllung soll deutlich lesbar sein.
- **Fön:** Aus **einer Spalte oder einem schmalen Zwischenraum** wird ein einzelner Buchstabe **oder ein ganzes Wort hervorgeblasen**.
- **Strohhalm:** Ein Buchstabe oder Wort liegt **am Boden eines Glases** und wird mit einem Strohhalm gerettet. Als zusätzliche Animationsidee können **die Buchstaben am Strohhalm entlang aus dem Glas hochklettern**.

Diese Werkzeuge ergänzen den Buchstabenmixer, Reißwolf, das geheime Glücksrad und die Zitruspresse. In jeder Szene soll das Werkzeug einen **plausiblen, spielerisch begründeten Zweck** erfüllen und eine tatsächliche Spur zugänglich machen. Es ist noch offen, in welchen Fällen und mit welcher konkreten Bedienung diese Effekte verwendet werden. Keine Änderung an Fall 01 daraus ableiten.

## Ermittlungshelfer: Ameise und andere kleine Helfer (16.11.2026)

**Status: neue Nutzeridee für spätere Detektivfälle; noch keine konkrete Figur, Handlung oder Animation festgelegt und nicht programmiert.**

- Eine **Ameise** oder ein anderer kleiner Helfer kann im Verlauf einer Ermittlung auftauchen und **einen weiteren Buchstaben bringen**, einen verlorenen Buchstaben transportieren oder **einen Hinweis auf die Lösung** liefern.
- Der Helfer kann beispielsweise an schwer zugängliche Orte gelangen und etwas finden, das das Würstchen selbst übersehen hat. So ergänzt er die bereits vorgemerkten Ermittlungswerkzeuge.
- Die Hilfe soll **zur Geschichte passen** und das Kind beim eigenen Entdecken unterstützen, statt die Lösung grundlos vorwegzunehmen.
- Ob die Ameise wiederkehrt oder je nach Fall unterschiedliche Tiere bzw. Figuren helfen, bleibt offen. Ebenso, ob der Helfer auf Anfrage oder überraschend erscheint.

## Bestätigte Wortspielidee: A-Meise (16.11.2026)

**Von der Nutzerin ausdrücklich bestätigt – konkrete Verwendung in einem Fall noch offen.**

Die Doppeldeutigkeit **„A-Meise“** entsteht als spielerische Verbindung von **einer Meise** und **dem Buchstaben A**. Eine Meise kann mit einem großen **A** im Schnabel angeflogen kommen und einen nützlichen Buchstaben für die Ermittlung bringen. Das Würstchen bemerkt den Wortwitz („Eine A-Meise!“). Der Buchstabe kann anschließend als Hinweis in einem Rätsel gebraucht werden.

Der Witz ist bewusst **A + Meise**, nicht bloß eine gewöhnliche Ameise als Tierhelfer. Die konkrete Szene, der Einsatzort und die Animation sind noch zu entwickeln.

## Ideenpool: versteckte Buchstaben in Gegenständen und Landschaften (16.11.2026)

**Status: Zehn redaktionell zusammengestellte Vorschläge als Ideenpool, noch keine freigegebenen Fallrätsel, Grafiken oder Programmierung.** Ausgangsidee der Nutzerin: ein **A, das sich als Teil einer Tannenbaumzeichnung versteckt**. Die Form des Buchstabens soll möglichst aus der natürlichen Bildkontur entstehen, nicht einfach als aufgedruckter Buchstabe erscheinen.

| Buchstabe | Versteck im Bild | Erkennbare Form | Mögliche Verwendung als Hinweiswort |
|---|---|---|---|
| **A** | Tannenbaum: zwei schräge Äste mit Querast | Zwei Schenkel und Querstrich bilden ein A | **_ST → AST** |
| **H** | Gartenzaun: zwei Pfosten mit Querlatte | Senkrecht – waagerecht – senkrecht | **_UT → HUT** |
| **S** | Geschwungener Waldweg oder Spur im Schnee | Kontinuierliche S-Kurve | **_PUR → SPUR** |
| **O** | Rundes Vogelnest von oben | Geschlossener Ring | **T_R → TOR** |
| **T** | Wegweiser: Pfahl mit waagerechtem Schild | Senkrechter Stamm, Querbalken oben | **_ISCH → TISCH** |
| **U** | Hufeisen am Scheunentor | Deutlich offenes U | **_HR → UHR** |
| **M** | Silhouette zweier Bergspitzen | Zwei Spitzen und mittlere Senke; Außenkanten ergeben M | **_AUS → MAUS** |
| **N** | Geländer: zwei Pfosten mit schräger Strebe | Zwei senkrechte Linien und verbindende Diagonale | **_ASE → NASE** |
| **V** | Astgabel oder Vogelflügel in V-Stellung | Zwei schräge Linien treffen sich unten | **_OGEL → VOGEL** |
| **Z** | Blitzspur oder zickzackförmiger Riss | Zwei waagerechte Stücke und verbindende Diagonale | **_AUN → ZAUN** |

### Einsatzprinzip

1. Das Kind findet den **Buchstaben im Bild** (Entdeckungsaufgabe).
2. Es kann die Form bei Bedarf mit einem Finger nachfahren oder durch einen optionalen Hinweis hervorheben lassen. Die Visualisierung darf den Fund nicht von Beginn an verraten.
3. Der gefundene Buchstabe wandert in den **Rucksack** beziehungsweise ergänzt eine **in der Fallhandlung begründete Wortlücke**.
4. Die Wortlösung führt zu einer **wirklichen nächsten Spur**. Nicht jeder Buchstabe muss in demselben Fall genutzt werden.
5. Die Hilfen sind gestuft: erst aufmerksam machen, dann den Bildbereich eingrenzen, erst zuletzt den Buchstaben nachzeichnen.

### Gestalterische und pädagogische Prüfung vor Umsetzung

- Der Buchstabe muss sich **ohne künstliche Verzerrung** plausibel aus dem Gegenstand ergeben; einige Varianten (besonders M und N) benötigen präzise Bildgestaltung.
- Nicht die ganze Szene mit dekorativen Buchstaben überfrachten; der gesuchte Buchstabe muss auch auf Smartphones und bei unabhängigem Bild-/Schriftzoom erkennbar sein.
- **A im Tannenbaum** ist die konkrete Nutzerskizze. Die neun weiteren Verstecke und alle Beispielwörter sind redaktionelle Vorschläge, keine von der Nutzerin bestätigten Einzelrätsel.
- Wortlücken sind illustrative Beispiele. In einem tatsächlichen Fall müssen Ort, Handlung und Hinweise diese Wörter nachvollziehbar motivieren.
- Diese Sammlung ersetzt **weder** die bereits bestätigte **A-Meise** **noch** die Szene mit dem **H** im Rucksack aus Fall 01.

## Änderungsverlauf

- **16.11.2026:** Zehn Vorschläge für bildintegrierte versteckte Buchstaben (A/H/S/O/T/U/M/N/V/Z) mit möglichen Hinweiswörtern aufgenommen; nur A im Baum stammt als konkrete Vorlage von der Nutzerin, übrige Vorschläge bleiben offen.

- **16.11.2026:** Wortspiel „A-Meise“ als ausdrücklich bestätigte Idee aufgenommen; Meise bringt A im Schnabel. Noch keine Umsetzung/Zuordnung.

- **16.11.2026:** Ameise und mögliche weitere kleine Helfer als Hinweis- oder Buchstabenbringer in das Ideenrepertoire aufgenommen; noch keiner Fallakte zugeordnet.

- **16.11.2026:** Besen, Teppichklopfer, Fön und Strohhalm samt Buchstaben-/Wortfund und möglicher Kletteranimation als neue Werkzeugideen aufgenommen; noch keine Fallzuordnung.

- **16.11.2026:** Zitruspresse als weiteres mögliches Ermittlungswerkzeug vorgemerkt: Einen fehlenden Buchstaben herauspressen und später als Hinweis nutzen. Nicht für Fall 01 festgelegt.

- **16.11.2026:** Neue Schneemann-Szene mit SAHNE → NASE + H im Rucksack nach Nutzeridee aufgenommen; vorläufige Fortsetzung mit HUT, verborgenem Glücksrad, KISTE und möglicher Auflösung als separaten Fallentwurf dokumentiert.

- **15.11.2026 (Ergänzung):** Geheimes Glücksrad als verstecktes Ermittlungswerkzeug mit Türspuren und später nutzbarem Buchstaben festgehalten. Das **Würstchen im gestreiften Pyjama mit Krönchen** als Markenzeichen bestätigt.

- **15.11.2026:** Wortpaare und erster HTML-Testfall; erzählerische Schwäche bei MAUS → HAUS festgestellt.
- **15.11.2026:** Glücksrad und Reißwolf vorgeschlagen; ein Spiel mit mehreren Fällen, Pinnwand und Wahl Zufallsakte/eigene Akte bestätigt.
- **15.11.2026:** Neues Repository für getrennte Entwicklung vereinbart; GitHub als zentraler Ablageort der Spielakte festgelegt; Dokumentation erstellt.
