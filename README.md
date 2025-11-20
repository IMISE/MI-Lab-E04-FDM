## MI-Lab Übung E04-FDM
# Registrierung von Forschungsvorhaben und Ablage in einem Forschungsdatenmanagementsystem

## Lokale Installation
Navigieren Sie in den Ordner **Setup** und führen dort im Terminal `docker-compose up -d` aus. Das zieht alle Docker images von einem Server. Der Download dauert ca. 5 min. 
Nachdem alle Images gestartet sind können Sie im Browser http://localhost:3000 aufrufen um auf den lokalen Local Data Hub zuzugreifen und sich anzumelden.

## Ordnerstruktur
- `Aufgaben/` Beinhaltet Übungsblatt, Präsentationsfolien und Lösungen
- `Material/`
  -  `Datensatz/` Der MIMIC-Datensatz für diese Übung in CSV-Format
  -  `Studiendokumente/` Die synthetischen Studiendokumente zum Hochladen in das Forschungsdatenmanagementsystem. 
- `Setup/` Docker Compose Setup für LDH

## Studiendokumente
Eine Übersicht der synthetischen zu hochladenden Studiendokumente für den MIMIC IV Demo Datensatz:

| Dokument | Beschreibung |
|----------|----------|
| Forschungsdatenmanagementplan (FDMP) | Wie Forschungsdaten erstellt, verarbeitet, gespeichert und geteilt werden |
| Studienprotokoll | Enthält Ziel, Design und Methodik der Studie  | 
| Datenqualitätsregeln | Standards und Kriterien für die Datenqualität  | 
| Data Dictionary | Struktur und Variablen des Datensatzes. Erleichtert Interpretation der Daten | 
