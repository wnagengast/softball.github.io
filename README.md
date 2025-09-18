# Arup Softball Stats — GitHub Pages cleanup

What I changed

- Replaced the original frameset-based `Index.html` (Excel export) with a simple static landing page that links directly to the exported sheet HTML files.
- Created a `player-pages/` folder with kebab-case redirect pages (e.g. `player-pages/adam-brooks.html`) that immediately redirect to the original files in the `Player Pages/` folder. This provides nicer, GitHub Pages–friendly URLs without changing the exported files or their asset folders.

Why

- GitHub Pages doesn't support the Excel frameset and the generated JavaScript tab strip. The new index and redirects let visitors open the exported HTML sheets and player pages directly.

Next steps (optional)

- Rename all exported files and their associated asset folders to kebab-case (e.g. `Player Pages/Adam Brooks.html` -> `player-pages/adam-brooks.html`, and `Player Pages/Adam Brooks_files/` -> `player-pages/adam-brooks_files/`) and update internal asset links. This would remove the need for redirect pages and produce cleaner on-disk layout.
- Move season sheets out of the `Arup Softball Stats_files/` folder into a `sheets/` directory and update `Index.html` links.
- Generate an automatic player index page from the `Player Pages/` directory.

If you'd like me to perform any of the optional steps, tell me which and I'll proceed.
