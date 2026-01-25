# PrimeChecker

Dieses Projekt demonstriert eine grundlegende Continuous Integration (CI)-Pipeline unter Verwendung von GitHub Actions für eine Java-Anwendung.

Abgeschlossene Schritte
Einrichtung des Repositorys: Erstellung eines öffentlichen GitHub-Repositorys mit einer Java-spezifischen .gitignore-Datei.

Lokale Umgebung: Klonen des Repositorys lokal und Einrichtung der erforderlichen Verzeichnisstruktur .github/workflows.

Workflow-Implementierung:

Konfiguration eines Demo-Workflows zur Überprüfung der GitHub Actions-Konnektivität.

Implementierung eines sekundären Build & Test-Workflows, der einen Ubuntu-Runner einrichtet, JDK 17 installiert und bei jedem Push automatisch JUnit 4-Tests ausführt.

Entwicklung des Quellcodes: Hinzufügen von PrimeCheck.java mit einer Logik zur Identifizierung von Primzahlen unter Verwendung einer optimierten Schleife.

Unit-Tests und Debugging:

PrimeCheckTest.java integriert, um Randfälle, negative Zahlen und Primzahlen/Nicht-Primzahlen zu validieren.

Anfängliche Testfehler behoben, um sicherzustellen, dass die CI-Pipeline den Status "bestanden" (grün checkmark) erreicht.
