.. _intro:

Kurzüberblick
=============

mediaTUM ist freie Python-Software zur flexiblen Verwaltung von Text-, Bild- und Video-Dateien sowie sonstigen Forschungsdaten.
Es ermöglicht die Erschließung, Veröffentlichung, Administration, Recherche und Verbreitung von Publikationen mit
und ohne Volltext (z.B. als Open-Access-Repository oder als Hochschulbibliographie).
Die Metadaten zu einer Objektdatei können während des Veröffentlichungsprozesses über ein Online-Formular eingegeben und
von entsprechend berechtigten Personen administriert werden. mediaTUM zeichnet sich durch sein flexibles Rechtemanagementsystem aus,
bei dem Zugriffrechte bis hin zur Ebene einzelner Objekte festgelegt werden können.
Die in mediaTUM hinterlegten Daten können komfortabel über Webschnittstellen in andere Anwendungen integriert und nachgenutzt werden.

mediaTUM ist geeignet für verschiedene Einsatzszenarien:

* Verwendung als Repository für Bild- und Videodateien:
   * Dateiformate und Objekttypen: JPG, TIFF, MP4
   * Beliebige Anpassbarkeit der vorhandenen Metadatenschemata aus dem Bereich Video und Bild
   * Uploadfunktion für einzelne Bilddateien oder komplette Archive
   * Automatische Extraktion von Bild-Metadaten wie z.B. EXIF-Daten
   * Darstellung eines Objektes in unterschiedlichen Auflösungen
   * Zoomfunktion bei Bildobjekten

* Verwendung als Volltextschriften-Server:
   * Unterstützung verschiedener PDF-Dateiformate: PDF-X, PDF-A
   * Ablage von PDF-Dateien und Volltextsuche über alle Dokumente
   * Automatische Extraktion von Metadaten aus PDF-Dateien
   * Anpassbare Metadatenschemata (wie oben)

* Verwendung als Hochschulschriften-Server für elektronische Dissertationen:
   * Integration der OAI-Schnittstelle zur Deutschen Nationalbibliothek
   * URN-Generierung
   * Workflow-Funktion mit definierten Bearbeitungsschritten wie Upload, interne Weiterbearbeitung für ausgewiesene User,
     Freigabe des Objektes zur Präsentation im Internet

In allen Anwendungsfällen wird zusätzlich bereitgestellt:

* Flexible Definition von Masken, die das selektive Editieren und Anzeigen von Metadatenfeldern erlauben
* Export im BibTeX-Format
* Eine Webschnittstelle um Datensätze im XML- oder JSON-Format abzurufen

Der Quellcode von mediaTUM ist verfügbar unter `github.com/mediatum <https://github.com/mediatum>`_.
Beiträge zur Weiterentwicklung in Form von *pull requests* sind willkommen.
