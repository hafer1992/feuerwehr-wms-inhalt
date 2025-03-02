# feuerwehr-wms-inhalt
Grundstruktur für ein Wissensmanagementsystem (WMS) einer Feuerwehr oder BOS.

Das WMS basiert auf der Software [DokuWiki](https://www.dokuwiki.org/).

In diesem Repository findet sich eine **Basisstruktur** für die Inhalte in dem WMS, welche aus der deutschlandweiten [Umfrage](https://ojs.iscram.org/index.php/Proceedings/article/view/64) im Jahr 2023 abgeleitet wurden.
Für die eigene Feuerwehr oder BOS müssen die Inhalte natürlich angepasst werden.

Zum Importieren der Basisstruktur muss der Inhalt des Ordners `pages` in den Ordner `pages` der eigenen DokuWiki Instanz verschoben werden. Dieser findet sich unter `data/pages`.

Bei allen Seiten, die man neu anlegt, wird der Inhalt aus der Datei `_template.txt` als Template eingefügt, um einen Ansatzpunkt zu haben. Dieses Template kann man verwenden, anpassen (Inhalt der Datei `_template.txt` bearbeiten) oder löschen (Datei umbenennen oder löschen).
