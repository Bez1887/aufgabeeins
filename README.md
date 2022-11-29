# Terminal Cheat Sheet Möglichkeiten


### Git mit Terminal 

code | english | deutsch
--- | --- | ---
*git clone* | Copy a repo from Github locally | Ein Repo von Github lokal kopieren
*git add .* | Add changes | Änderungen hinzufügen
*git commit -m "Place commit here"* | Add comment what was changed | Kommentar hinzufügen, was gemacht wurde
*git push* | Copy the file to github | Kopiert die Datei wieder auf Github
*git status* | Displays the status | Gibt den Status aus
*git log* | List of all activities | Auflistung aller Aktivitäten




### File Manipulation

code | english | deutsch
--- | --- | --- |
*mkdir*|Create a new directory| Neuen Ordner erstellen
*touch*|Create a new, empty file, or update the modified time of an existing one| Neue Datei erstellen (Dateinamen + Dateiendung mit angeben Bsp.: touch style.css)
*cp -a* | Copy with all rights | Kopiert mit allen Rechten
*cp <Dateiname_alt.txt> <Dateiname_neu.txt>* | Copy file with a given name | Eine Datei wird mit entsprechenden Namen dupliziert und kopiert
*mv -rvf* | Move or rename file or directory | Verschieben oder Umbenennen von Dateien und Ordnern
*mv <Dateiname_alt.txt> <Dateiname_neu.txt>* | Rename File | Dateiname ändern, aber wenn es den Dateinamen schon gibt, wird die Datei überschrieben
*mv -i* | Name change with advance warning | Namensänderung mit Vorwarnung
*mv <dateiname.txt> Ordnername* | Move file to folder| Datei in Ordner verschieben 
*rm* | Delete file | Datei löschen
*rm -rf* Ordnername| Delete folder | Ordner löschen
*chmod -R 777* | Change the file permissions for a file or directory | Vergibt für User, Gruppe & Anderen für alle Unterverzeichnisse read, write, execute Rechte
*chmod 777 Verzeichnispfad*| Change the file permission for a special folder |Vergibt für User, Gruppe & Anderen für einen speziellen Ordner read, write, execute Rechte
*cat > file* | Create a new file with the text you type after | Neue Datei mit Text erstellen
*cat file*|View the contents of a file| Inhalt einer Datei anzeigen
*greb*|View the contents of a file that match a pattern | Zeigen Sie den Inhalt einer Datei an, die einem Muster entspricht
***

#### Verschie. Markdown Syntax/Shortcuts

<!-- z.b für Checkliste -->
- [x] Checkliste



##### Auf Git Hub anschauen 
1. git status
2. git add . <!-- ich will alles hochladen der Punkt steht für alle im Ordner -->
<!-- wenn die Bilder auch auf GitHub zu sehen sein sollen, dann  --> 
3. git commit -m "add images"
4. git commit -m + Enter
2. git commit -m "Name" + Enter
3. git push 
4. Refresh Page 

