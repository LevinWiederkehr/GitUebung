A: Linus Torvalds entwickelte Git als ein verteiltes Versionskontrollsystem. 
   Es ermöglicht Entwicklern, Änderungen am Quellcode zu verfolgen, zu verwalten und zu teilen.
   Git unterstützt die Zusammenarbeit von Teams, ermöglicht das Arbeiten in isolierten Branches
   und bietet Funktionen zur Rückverfolgung von Änderungen und Wiederherstellung.
   Es ist ein Standardwerkzeug in der Softwareentwicklung.
 
B:
# Git-Repository initialisieren
git init
 
# Änderungen für den Commit markieren
git add <dateiname>
 
# Commit erstellen mit einer Nachricht
git commit -m "Commit-Nachricht"
 
# Branch erstellen
git branch <branchname>
 
# Branch wechseln
git checkout <branchname>
 
# Änderungen vom Remote-Repository abrufen und integrieren
git pull origin <branchname>
 
# Lokale Änderungen zum Remote-Repository hochladen
git push origin <branchname>