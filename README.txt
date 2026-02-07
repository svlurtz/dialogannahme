SO NUTZT DU DIE OFFLINE-APP (PWA) AUF DEM iPAD

1) ZIP entpacken.
2) tailwind.min.css (Tailwind 2.2.19) herunterladen und die Platzhalter-Datei ersetzen.
3) jspdf.umd.min.js (jsPDF 2.5.1 UMD) herunterladen und die Platzhalter-Datei ersetzen.
4) Den ganzen Ordner per HTTPS hosten (OneDrive ist oft problematisch, besser: GitHub Pages / Cloudflare Pages).
5) Auf dem iPad in Safari öffnen: Dialognannahme.html
6) Einmal warten bis geladen → dann Teilen → "Zum Home-Bildschirm".
7) Offline testen: Flugmodus an → App öffnen.

Hinweis: Wenn die Seite ohne Layout erscheint, wird tailwind.min.css nicht geladen (falscher Ort oder leer).
