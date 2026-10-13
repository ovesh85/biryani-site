Zafraan: realistic biryani scroll site (static version)

Open it
  Double-click index.html. Chrome, Edge, Firefox and Safari all play it.
  If the scroll feels jumpy when opened as a file, serve the folder instead:
    cd zafraan-site
    python3 -m http.server 8000
  then open http://localhost:8000

What's inside
  index.html            page, styles and scroll script (content arrays at the top of the script)
  assets/video/         six 1920px clips, one per cooking step, plus a poster (first frame) each
  assets/img/           menu photos, order-band photo, favicon

Tuning
  SCROLL_PER_SCENE in the script sets how much scroll each step takes (default 170 = 1.7 screens).
