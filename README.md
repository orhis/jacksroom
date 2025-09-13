# Poker Room – Jack’s Room (One‑page, Bootstrap 5)

**Jak użyć:**

1. Otwórz `index.html` lokalnie w przeglądarce (lub użyj VS Code + Live Server).
2. Podmień treści (nazwy, opisy, kontakt) w `index.html`.
3. Wygeneruj własne obrazy AI i zamień pliki w `assets/` (`hero.webp`, `about.webp`, `og.jpg`, `favicon.ico`).

**Formularz kontaktowy:**  
- Zmień `action="#"` na swój endpoint, np. Formspree: `https://formspree.io/f/XXXXXXX`.
- Honeypot (`_gotcha`) ogranicza spam. Po wdrożeniu sprawdź działanie formularza.

**Darmowy hosting:**  
- **Netlify**: przeciągnij folder na app.netlify.com (plik `_headers` doda polityki bezpieczeństwa).  
- **GitHub Pages**: ustaw Pages -> branch `main`/root.  
- **Vercel**: „New Project” i wskaż repo.

**Bezpieczeństwo:**  
- `_headers` ma HSTS, CSP, Referrer-Policy itd. Dostosuj `form-action` do wybranej usługi formularza.  
- Jeśli użyjesz lokalnych plików Bootstrap zamiast CDN, uprościsz CSP.

**Rozwój w przyszłości:**  
- Odkomentuj w nawigacji sekcje `Szachy` i `Planszówki` i dodaj nowe `<section>` z treściami.

Powodzenia! ♟️🃏
