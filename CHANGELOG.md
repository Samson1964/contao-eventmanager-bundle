# Eventmanager Changelog

## Version 0.1.1 (2026-07-29)

* Fix: Warning: Undefined array key "deleteConfirm" bei contao:migrate -> Lesezugriffe auf $GLOBALS['TL_LANG'] in den DCA-Dateien mit `?? null` bzw. `?? array()` abgesichert, da der DcaLoader die Sprachdateien noch nicht geladen hat

## Version 0.1.0 (2024-04-17)

* Add: Abhängigkeit codefog/contao-haste
* Add: PHP-8-Unterstützung
* Add: Haste-Toggler
* Change: Beschreibung, Keywords und Homepage in der composer.json ergänzt, damit Packagist das Paket verständlich darstellt und über die Suche auffindbar macht

## Version 0.0.1 (2022-05-25)

* Grundstruktur erstellt
