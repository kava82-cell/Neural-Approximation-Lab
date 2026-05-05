Neural Approximation Lab
​Übersicht
​Dieses Projekt ist eine webbasierte Implementierung eines künstlichen neuronalen Netzes (KNN) zur Visualisierung der Funktionsapproximation. Es dient der Demonstration des Universal-Approximations-Theorems, nach dem ein neuronales Netz mit einer ausreichenden Anzahl an Neuronen und geeigneten Aktivierungsfunktionen jede beliebige kontinuierliche Funktion abbilden kann.
​Die Anwendung wurde in reinem JavaScript (Vanilla JS) ohne externe Deep-Learning-Bibliotheken entwickelt, um die zugrunde liegende Mathematik und den Lernprozess (Backpropagation) transparent darzustellen.
​Technische Spezifikationen
​Engine: Eigenständige JavaScript-Implementierung einer Neural-Network-Klasse.
​Lernverfahren: Stochastischer Gradientenabstieg (SGD).
​Rendering: p5.js für die Echtzeit-Visualisierung der Topologie und der Funktionskurven.
​Styling: Tailwind CSS für das Interface-Design.
​Architektur: Frei konfigurierbare Anzahl an Hidden Layers und Neuronen pro Layer.
​Kernfunktionen
​Architektur-Manipulation: Anpassung der Schichttiefe und Neuronenanzahl während des laufenden Trainings.
​Aktivierungsfunktionen: Vergleich von ReLU (stückweise linear), Sigmoid und Tanh (glatt) hinsichtlich ihrer Approximationscharakteristik.
​Echtzeit-Feedback: Überwachung des Mean Squared Error (MSE) und visuelle Darstellung der Gewichtsanpassungen in der Netzwerktopologie.
​Funktions-Varianten: Auswahl zwischen Sinuswellen, Polynomen dritten Grades und Sprungfunktionen zur Analyse der Anpassungsfähigkeit des Modells.
​Mathematischer Hintergrund
​Das System nutzt den Vorwärtspass zur Prädiktion und den Rückwärtspass (Backpropagation) zur Fehlerkorrektur. Die Ableitungen der Aktivierungsfunktionen sind explizit implementiert, um die Gewichte in Richtung des negativen Gradienten der Verlustfunktion zu optimieren.
​Installation und Betrieb
​Da das Projekt auf Standard-Webtechnologien basiert, ist keine lokale Installation von Abhängigkeiten erforderlich.
​Klonen des Repositories.
​Öffnen der index.html in einem modernen Webbrowser.
​Die benötigten Bibliotheken (Tailwind, p5.js) werden über CDNs geladen.
​Lizenz
​Dieses Projekt wird unter der MIT-Lizenz zur Verfügung gestellt.
