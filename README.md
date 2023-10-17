# mySite

Dokumentation: Mein Terminplaner

<img width="318" alt="Bildschirmfoto 2023-10-17 um 02 08 33" src="https://github.com/AppNewbie86/mySite/assets/101304191/7ac5d0ab-d86b-45b9-b6b5-ae0b99fb92cf">
<img width="1189" alt="Bildschirmfoto 2023-10-17 um 02 09 18" src="https://github.com/AppNewbie86/mySite/assets/101304191/18f28fd0-7f3a-4857-918b-ebb2c5d44386">
<img width="1156" alt="Bildschirmfoto 2023-10-17 um 02 10 17" src="https://github.com/AppNewbie86/mySite/assets/101304191/1db982a7-47f1-4340-bb2c-85dc68909ace">

Einführung

Dieses Dokument dient der Erklärung und Dokumentation eines einfachen Terminplaners, 
der mithilfe von HTML, CSS und JavaScript erstellt wurde. Der Terminplaner ermöglicht es Benutzern, Aufgaben hinzuzufügen, 
sie als erledigt zu markieren und Feedback zu diesen Aufgaben zu geben.

HTML-Struktur

Der HTML-Code für den Terminplaner enthält die grundlegende Struktur einer Webseite und definiert die Elemente für die 
Darstellung von Aufgaben und die Benutzeroberfläche.

<!DOCTYPE html>

Dieser Tag deklariert die HTML-Version, die in diesem Dokument verwendet wird.

<html lang="de>
  
Hier wird die HTML-Datei geöffnet, und die Sprache der Webseite wird auf Deutsch festgelegt.

<head>
  
Der Kopfbereich der Webseite, in dem Metadaten und CSS-Styles definiert werden.

Metadaten

charset="UTF-8": Definiert die Zeichenkodierung als UTF-8 für die richtige Anzeige von Sonderzeichen.
name="viewport": Stellt sicher, dass die Webseite auf verschiedenen Bildschirmgrößen korrekt dargestellt wird.
<title> Definiert den Titel der Webseite, der im Browser-Tab angezeigt wird.

<style>
  
In diesem Bereich wird das CSS für das Design des Terminplaners definiert.

CSS-Styling
  
Das CSS definiert das Erscheinungsbild des Terminplaners. Es wurde ein "Buch"-Design-Look erstellt, der an ein Buch erinnert.

JavaScript-Code
  
Der JavaScript-Code ist für die Interaktivität des Terminplaners verantwortlich. Er wird erst nach dem Laden der Seite ausgeführt, um sicherzustellen, dass die HTML-Elemente bereits vorhanden sind.

Aufgabenliste
  
taskList: Das <ul>-Element, das die Liste der Aufgaben enthält.
  
Aufgaben hinzufügen
  
taskInput: Ein <input>-Feld, in das der Benutzer neue Aufgaben eingeben kann.
addTaskButton: Ein <button>, um neue Aufgaben der Liste hinzuzufügen.
  
Interaktionen
  
Der JavaScript-Code reagiert auf verschiedene Interaktionen der Benutzer:

Klicken auf "Löschen": Entfernt die ausgewählte Aufgabe aus der Liste.
Klicken auf "Erledigt": Markiert die ausgewählte Aufgabe als erledigt (durchgestrichener Text).
Klicken auf "Feedback geben": Ermöglicht es Benutzern, Feedback zu einer Aufgabe hinzuzufügen.
  
Fazit
  
Der "Mein Terminplaner" ist eine einfache Anwendung, die es Benutzern ermöglicht, Aufgaben zu verwalten, sie als erledigt zu markieren 
und Feedback hinzuzufügen. Das Design wurde in einem Buchstil erstellt, um die Benutzererfahrung interessanter zu gestalten. 
Diese Dokumentation bietet eine Übersicht über die Struktur und Funktionalität des Terminplaners und kann als Ausgangspunkt für 
Erweiterungen und Anpassungen dienen.
