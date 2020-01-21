### NUTZERMODELLE IN DER MCI

### Welche Arten von (Nutzer-)Modellen lassen sich für den Bereich der MCI unterscheiden? Nennen Sie Beispiele und erläutern diese.
- **deskriptive Modelle** (Analogien und Metaphern)
    - **Handlungsphasenmodell:** Modell für Beschreibung menschlicher Handlungen mithilfe technischer Systeme
- **prädiktive Modelle** (z.B. mathematische Gleichungen)
    - **Fitt's Law:** Model of human movement which predicts the time required to rapidly move to a target area

### Welche möglichen Funktionen haben (Nutzer-)Modelle in der MCI?
- schaffen Verständnis für das Verhalten komplexer Systeme
- unterstützen Gestaltung und Evaluation

### Beschreiben Sie das Handlungsphasenmodell von D.A. Norman.
- kognitionspsychologisches Modell zur Beschreibung menschlicher Handlungen mithilfe technischer Systeme
- im Fokus steht die Sicht des Nutzers auf die Nutzungsschnittstelle
- Wahrnehmung, Handlungsplanung und Handlungsregulation
- Transformationen von der Zielsetzung zu konkreten Eingabehandlungen über die Wahrnehmung von Systemausgaben bis zur Bewertung

**Gulf of execution:** Mismatch zwischen den Intentionen des Nutzers und den erlaubten Aktionen
**Gulf of evaluation:** Mismatch zwischen dem vom Nutzer erwarteten Verhalten und dem tatsächlichen Systemverhalten

**Handlungsziel**
--> Absicht zu handeln --> Spezifikation der Handlung --> Ausführung der Handlung &nbsp;&nbsp;&nbsp;&nbsp; **(intention)**
--> Wahrnehmung --> Interpretation --> Bewertung &nbsp;&nbsp;&nbsp;&nbsp; **(evaluation)**
--> **Handlungsziel**

**Anwendung:** Gestaltung und Evaluation

### Welche Konsequenzen ergeben sich aus dem Handlungsphasenmodell von D.A. Norman für die Gestaltung interaktiver Systeme?

### Erläutern Sie die Modellkomponenten von Fitts' Gesetz.

### Welche Modellkomponenten von Fitts' Gesetz sind für die Evaluation von Zeigegeräten aussagekräftig? Warum?

### Welche Konsequenzen ergeben sich aus Fitts' Gesetz für die Gestaltung von Benutzungsoberflächen?

### Erläutern Sie das GOMS-Modell an Hand der Kernkomponenten des Modells.
Methode, um eine Aufgabe und das Wissen des Nutzers, wie man diese Aufgabe löst, zu beschreiben.
- **Goals:** Ziele des Benutzers
- **Operators:** Aktionen, die die Software dem Benutzer ermöglicht (CUI --> Befehle / GUI --> Menüs, Buttons etc.)
- **Methods:** Gelernte Sequenzen von Teilzielen und Operatoren, um ein Ziel zu erreichen
- **Selection Rules:** Persönliche Regeln, denen Nutzer folgen, wenn es darum geht, zu entscheiden, welche Methode unter bestimmten Umständen zu nutzen ist

Bsp.:
The fox jumps over the lazy quick brown dog.
- **top-level-goal:** move "quick brown" before "fox"
- **subgoal:** highlight text
- **operators:**
    - move mouse
    - click mouse button
    - type characters
- **methods:**
    - for the editing goal:
        1. delete word and retype
        2. cut-and-paste using keyboard shortcuts
        3. cut-and-paste using menus
    - for the highlighting subgoal:
        1. drag across text
        2. double click first, shift click last
- **selection rules:**
    - for the editing goal:
        - if test is only one or two chars long --> use retpye method
        - else if remember shortcuts --> use shortcut method
        - else use all-clicking method
    - for the highlighting subgoal:
        - if text to be moved not whole words --> use dragging method
        - else use all-clicking method

### Welche möglichen Anwendungskonsequenzen sind mit dem GOMS-Modell Verbunden?

### Nennen Sie drei Kritikpunkte am GOMS-Modell.
- reduktionistischer Ansatz
- Beschränkung auf fehlerfreies Modellverhalten
- eingeschränkte Validität der Modellannahmen
