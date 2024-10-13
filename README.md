# Römische Kaiserinschriften in Germanien - eine historische Netzwerkanalyse #

*Erstellt für das Seminar „Die Methode der Netzwerkanalyse in Theorie und Praxis“*

*von Antonia Friedrich, Universität Stuttgart, M.A. Digital Humanities*

Die Idee des Netzwerks sollte eine Visualisierung von römischen Inschriftenfunden mit ihren im Text genannten oder der Datierung nach entprechenden zuzuordneten Kaisern sein. Dabei sollte die römische Herrschaft im Gebiet der germanischen Provinzen und entlang des Grenzflusses Rhein betrachtet werden.

Hierfür wurde auf die Inschriftendaten aus der Epigraphischen Datenbank Clauss/Slaby (EDCS) zurückgegriffen: https://db.edcs.eu/epigr/epi.php?s_sprache=de

Alle Inschrifteneinträge in der Datenbank zu den römischen Provinzen konnten für die Seminararbeit nicht verwendet werden, daher wurde mit den Filtereigenschaften "Provinz: Germania superior" und "Germania inferior", "Material: lapis" sowie mit "Inschriftengattung/Personenstatus: et;Augusti/Augustae" die Suche in der Datenbank eingerenzt.

Für die Provinz Germania superior wurden insgesamt 219 Inschrifteneinträge zu Augusti/Augustae auf Stein gefunden, für die Provinz Germania inferior waren es 96 Einträge. Diese wurden manuell in eine Excel-Tabelle übertragen und gesammelt, bevor Einträge mit ungenauen Datierungen oder Textinhalten sowie einem fehlendem Fundort aufgrund der Fragestellung der Netzwerkanalyse aussortiert wurden. 
Des Weiteren wurden die zugehörigen Kaiser, falls nicht in der EDCS im Inschriftentext erkennbar, auf der Seite der Epigraphischen Datenbank Heidelberg oder der Römischen Kaisertabelle von Dietmar Kienast et al. recherchiert.

Die Liste "Kanten_Inschriftennetzwerk.csv" enthält die bereinigte Liste an Inschriftenfunden mit ihrem jeweilgen Fundort, der jeweilgen Datierung und den erwähnten oder zuzuordneten Kaisern mit ihrer Dynastie oder Kaiserepoche (z.B: Julisch-claudisch, Flavier, Adoptivkaiser, Erbkaiser, Severer, Soldatenkaiser, Konstantiner und Tetrachisch). Für den Import im Visualisierungprogramm Gephi musste die Datierung in Intervalle formatiert werden.
