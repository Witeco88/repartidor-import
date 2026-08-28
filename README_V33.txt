# Repartidor v33 — Escaneig de tiquets

## Novetat
- Nova pantalla **Escanejar tiquet**.
- Foto des de la càmera de l’iPhone o selecció d’una imatge.
- OCR al navegador amb Tesseract.js.
- Detecció de línies amb imports i del total quan apareix al tiquet.
- Revisió manual de nom i import.
- Assignació A/B/C… a una o diverses persones.
- Productes compartits: l’import es divideix entre els seleccionats.
- Si el total detectat difereix de la suma de línies, la diferència es distribueix proporcionalment en aplicar.
- El resultat s’integra amb el motor de repartiment existent.

## Important
Aquesta és una primera versió funcional del lector. La lectura OCR depèn de la qualitat de la foto i del format del tiquet. La pantalla de revisió és obligatòria abans d’aplicar el resultat.

## GitHub Pages
Substitueix els fitxers del repositori pels d’aquest paquet i fes **Commit changes**. La PWA actualitza el cache a v33.
