Author Pods site — how to put it online

1. Upload this whole folder (keeping the layout exactly as is) to any
   static web host: your school/department web space, doenet.org hosting,
   GitHub Pages, Netlify, etc.
2. Open index.html in a browser, e.g.
   https://your-host.example/author-pods-site/

Notes
- Keep index.html, support.js and the assets/ folder together — the page
  loads the other two files by relative path.
- Serve it over http(s). Double-clicking index.html straight from the
  zip can be blocked by some browsers' local-file rules.
- Internet access is needed once per visitor for the fonts
  (Google Fonts: Fredoka + Nunito); everything else is in this folder.
