# Römische Kaiserinschriften in Germanien - eine historische Netzwerkanalyse #

*Erstellt für das Seminar „Die Methode der Netzwerkanalyse in Theorie und Praxis“*

*von Antonia Friedrich, Universität Stuttgart, M.A. Digital Humanities*

Die Idee des Netzwerks sollte eine Visualisierung von römischen Inschriftenfunden mit ihren im Text genannten oder der Datierung nach entprechenden zuzuordneten Kaisern sein. Dabei sollte die römische Herrschaft im Gebiet der germanischen Provinzen und entlang des Grenzflusses Rhein betrachtet werden.

Hierfür wurde auf die Inschriftendaten aus der Epigraphischen Datenbank Clauss/Slaby (EDCS) zurückgegriffen: https://db.edcs.eu/epigr/epi.php?s_sprache=de

Alle Inschrifteneinträge in der Datenbank zu den römischen Provinzen konnten für die Seminararbeit nicht verwendet werden, daher wurde mit den Filtereigenschaften "Provinz: Germania superior" und "Germania inferior", "Material: lapis" sowie mit "Inschriftengattung/Personenstatus: et;Augusti/Augustae" die Suche in der Datenbank eingerenzt. Hier liegt allerdings auch die Grenze der Aussagekraft dieses Netzwerks zur römischen Geschichte in Germanien, da der Einfluss von Ereignissen der römischen Grenzgeschichte in den benachbarten Provinzen Gallien, Rätien oder Noricum nicht beachtet wurde. Ihre Miteinbeziehung in das Inschriftennetzwerk sowie auch die Erweiterung des Materialstyps für Militärdiplome auf metallischem Material bspw. könnte in weiteren Analysen zu aussagekräftigeren Interpretation führen.

Für das Koprus wurden in der Datenbank für die Provinz Germania superior insgesamt 219 Inschrifteneinträge zu Augusti/Augustae auf Stein gefunden, für die Provinz Germania inferior waren es 96 Einträge. Diese wurden manuell in eine Excel-Tabelle übertragen und gesammelt, bevor Einträge mit ungenauen Datierungen oder Textinhalten sowie einem fehlendem Fundort aufgrund der Fragestellung der Netzwerkanalyse aussortiert wurden. 
Des Weiteren wurden die zugehörigen Kaiser, falls nicht in der EDCS im Inschriftentext erkennbar, auf der Seite der Epigraphischen Datenbank Heidelberg oder anhand der Römischen Kaisertabelle von Dietmar Kienast et al. (2017) recherchiert.

Die Liste "Kanten_Inschriftennetzwerk.csv" enthält die bereinigte Liste an Inschriftenfunden mit ihrem jeweilgen Fundort, der jeweilgen Datierung und den erwähnten oder zuzuordneten Kaisern mit ihrer Dynastie oder Kaiserepoche (z.B: Julisch-claudisch, Flavier, Adoptivkaiser, Erbkaiser, Severer, Soldatenkaiser, Konstantiner und Tetrachisch). Für den Import im Visualisierungprogramm Gephi musste die Datierung in Intervalle formatiert werden.

Für die Liste "Knoten_Ischriftennetzwerk" wurden die zugehörigen recherchierten Kaiser mit ihren Inschriftenfundorten verknüpft, indem alle Fundorte mit ihren geographischen Koordinaten und ihrer Provinz aufgelistet wurden. Die Koordinaten zu den jeweiligen Orten der Inschrifteneinträge und Kaiserresidenzen wurden mithilfe des LLM ChatGPT zusammengestellt: "Ich bin Historikerin, forsche im Bereich der Digital Humanities und möchte zu den unten aufgeführten römischen Kaisernamen in jeder Zeile jeweils pro Zeile einmal die Kaisernamen aufgelistet mit dem jeweiligen Regierungszeiträumen und dann den jeweiligen Residenzsitz der Kaiser in der jeweiligen Zeile mit Angabe der Quelle, wo die Information zu finden ist, und zusätzlich zu den Orten die georgaphischen Koordianten nach Wikidata und Geohack haben.
Hier ist die Liste der Kaiser: [...] Bei erfolgreicher Bearbeitung gibt es einen Belohnung!"

Aufgrund der Visualisierung mithilfe der Layouts "Map of Country" und "Geo Layout" enthalten die beiden .csv-Dateien unter den Inschriftenknoten die weiteren Knoten für die Kartenvisualisierung der Ländergrenzen.

Die einzelnen Netzwerkabschnitte sind als .png mit ihrer jeweiligen Zeitspanne und Dynastie gekennzeichnet und im Ordner "Netzwerkabschnitte nach Dynastien" zu finden. 

Die von Gephi erstellten dynamischen Times Series sind in den .png-Dateien nb-edges-ts und nb-nodes-ts sowie als .html report_edges sowie report_nodes zu finden.





_Zur Erstellung des Netzwerks verwendete Literatur:_

_Kienast, D., Eck, W. and Heil, M. (2017): Römische Kaisertabelle: Grundzüge einer römischen Kaiserchronologie. 6th edn. Darmstadt: Wissenschaftliche Buchgesellschaft._

_Tools_:

_Clauss, M. und Slaby, W. (o.J.): Epigraphische Datenbank Clauss/Slaby. URL: https://db.edcs.eu/ [Zugriff: 10. Oktober 2024]_

_Epigraphische Datenbank Heidelberg (o.J.): Epigraphische Datenbank Heidelberg. Zugriff: https://edh.ub.uni-heidelberg.de/ [Zugriff: 10. Oktober 2024]_
