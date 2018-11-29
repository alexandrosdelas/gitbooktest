Composer Sync 28.11.2018
Thomas:
- Jenkins Statische Codeanalyse, imer wenn Code bearbeitet wurde da in Packages gucken
- Jenkins Results Analyzer
Änderung im Stub der Rest-Schnittstelle (AND/OR Parameter)

Alex:
- Was brauchen wir für Dokumentation? 
	Wiki wie in Confluence
	Docs sollen im gleichen Repository liegen
	MD-Format bzw. nah am Code (in Stylesheet einpacken) reicht
	Doc soll am Ende als HTML-File/Wiki beim Kunden vorliegen
	Doc soll synchronized mit Git-Commits sein
	keine Anforderungen für FE
	Jekyll Ruby mit Container
	Next.js zu kompliziert
	GitBook first choice
	Stylesheets nicht kommerziell nutzbar?
	HTML und PDF wichtig
	GitBook hat Styles, kann HTML und PDF
- Next steps: Demo Dokumentation machen mit mehreren MD Files (manche included, indexes nice to have) und Images, Inhaltsverzeichnis, Source-Code, Klassendiagramm usw. mit GitBook. Wenn es schnell geht auch mit Jekyll. Soll aus gitLab automatisch gebaut werden um es als zip runterzuladen. doc-files im repository unter /doc/* (bis vor dem nächsten composer sync!)
- weitere fragen: file-struktur? (package)

Nikita:
- wie immer nichts

Alex:
- Rest Router Stubs Beispiel
