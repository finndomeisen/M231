# Modul 231


### Einleitung



This text is ***really important***.

# Befehle für den Alltag

git pull                                # pull all new commits from remote repository
# Um sich auf den neuesten Stand des Projektes zu bringen. 
# Das muss man jedesmal machen, bevor man beginnt! 

git add .   oder   git add <file>       # stage one or multiple files
# Damit mache ich alle neuen Dateien für den Git-Transport parat (=stage)


git commit -m "Ein Text für den Commit" # commit all staged files
# Damit schreibe ich das neue Git-Paket an. Die "Message" kann ich später 
# in der Commit-Liste sehen umvielleicht darauf zurückzugreifen.

git push                                # push all new commits to remote repository
# Damit schicke ich die aktuellen Arbeiten (in allen Dateien seit dem letzen pull)
# zum Online-Repository (-Projekt)

# Falls an einem neuen Projekt gearbeitet werden soll (braucht man nur 1x):

git clone <url>                         # clone remote repository in folder













# Beispiel Markdown Datei

## 1. Überschriften

Dies ist eine H1-Überschrift.
### H3-Überschrift
#### H4-Überschrift
##### H5-Überschrift

## 2. Text-Formatierungen

**Fetter Text**  
*Kursiver Text*  
***Fett und kursiv***  
~~Durchgestrichen~~

## 3. Listen

### Ungeordnete Liste
- Punkt 1
  - Unterpunkt 1
- Punkt 2

### Geordnete Liste
1. Erster Punkt
   1. Unterpunkt 1
2. Zweiter Punkt

## 4. Links

[Google](https://cdn-useast1.kapwing.com/static/templates/knee-surgery-tomorrow-meme-template-KAI3QQ5SCkNXSKMs-full.jpg)

## 5. Bilder

![Beispielbild](https://via.placeholder.com/150)

## 6. Zitate

> Dies ist ein Blockzitat. Zitate sind gut für das Hervorheben wichtiger Punkte.

## 7. Code

### Inline-Code
Hier ein Beispiel für Inline-Code: `print("Hallo Welt")`

### Codeblock
```python
def beispiel():
    print("Dies ist ein Python Codeblock")



