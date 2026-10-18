## Hi, I'm antnardo 👋

I write Python tools for the jobs I would otherwise keep doing by hand:
spreadsheets, PDF layout, LaTeX sources, class material. Most of them grew out
of teaching; ten became packages published on PyPI. Each package is typed,
tested in CI across the Python versions it supports, and used in my own work
before it is released.

### Published packages

| Package | PyPI | What it does |
| --- | --- | --- |
| [odsslicer](https://github.com/antnardo/odsslicer) | [![PyPI](https://img.shields.io/pypi/v/odsslicer)](https://pypi.org/project/odsslicer/) | Reads and writes `.ods` files (LibreOffice Calc) with numpy-style indexing, `sheet["A1:B3"]`, and keeps formats, formulas and styles on the way back. |
| [latexdetok](https://github.com/antnardo/latexdetok) | [![PyPI](https://img.shields.io/pypi/v/latexdetok)](https://pypi.org/project/latexdetok/) | A tolerant LaTeX tokeniser: a tree of groups and commands that rewrites the source byte for byte, and a `latexdetok check` command that says what is wrong better than TeX does. |
| [reportlab_layout](https://github.com/antnardo/reportlab_layout) | [![PyPI](https://img.shields.io/pypi/v/reportlab-layout)](https://pypi.org/project/reportlab-layout/) | A cursor-driven layout layer on top of reportlab: the flow of a document, with the canvas always within reach. |
| [enoncepdf](https://github.com/antnardo/enoncepdf) | [![PyPI](https://img.shields.io/pypi/v/enoncepdf)](https://pypi.org/project/enoncepdf/) | Reads exam statements in PDF: finds their headings and questions, and crops them into slices without headers, footers or line numbers. |
| [texformules](https://github.com/antnardo/texformules) | [![PyPI](https://img.shields.io/pypi/v/texformules)](https://pypi.org/project/texformules/) | LaTeX formulas typeset in one batch, cached as PNG and one-page PDF with their baseline. |
| [latex-figures](https://github.com/antnardo/latex_figures) | [![PyPI](https://img.shields.io/pypi/v/latex-figures)](https://pypi.org/project/latex-figures/) | matplotlib figures that match their LaTeX document: size in cm, fonts, preamble, decimal comma, cropping. |
| [trombinoscope](https://github.com/antnardo/trombinoscope) | [![PyPI](https://img.shields.io/pypi/v/trombinoscope)](https://pypi.org/project/trombinoscope/) | A printable photo directory from a folder of raw photos and a list: every face framed the same way, colours evened out across the batch. Documentation in French. |

### Other projects

- [icalsync](https://github.com/antnardo/icalsync): events with a stable key,
  kept up to date in macOS Calendar or in an iCalendar file, in French.
- [bpaye](https://github.com/antnardo/bpaye): a French teacher's payslips,
  computed, forecast and read back from the PDF, in French.
- [liveboxapi](https://github.com/antnardo/liveboxapi): a synchronous Python
  client for Orange Livebox routers.
- [synologygofilehosting](https://github.com/antnardo/synologygofilehosting) and
  [synodl-firefox](https://github.com/antnardo/synodl-firefox): two small
  add-ons for Synology Download Station.

Bug reports and questions are welcome in the issues of each repository.

### En français, enseignement de la physique

| Package | PyPI | What it does |
| --- | --- | --- |
| [titrages](https://github.com/antnardo/titrages) | [![PyPI](https://img.shields.io/pypi/v/titrages)](https://pypi.org/project/titrages/) | Calcul de pH et de potentiel de mélanges, affichage de courbes de titrages - package autonome LuaLaTeX disponible |
| [thermodiagrammes](https://github.com/antnardo/thermodiagrammes) | [![PyPI](https://img.shields.io/pypi/v/thermodiagrammes)](https://pypi.org/project/thermodiagrammes/) | Surcouche de CoolProp pour les diagrammes d'états thermodynamiques, API simplifiée pour un tracé rapide de diagrammes et de cycles |
| [fieldlines](https://github.com/antnardo/fieldlines) | [![PyPI](https://img.shields.io/pypi/v/fieldlines)](https://pypi.org/project/fieldlines/) | Affichages simplifié de lignes de champ, sources électrostatiques et magnétostatiques prédéfinies |
| [grandeursphy](https://github.com/antnardo/grandeursphy) | (hors pypi) | Grandeurs physiques avec unités (pint), incertitudes, constantes CODATA 2022 et sortie siunitx pour pythontex |
| [pychimie](https://github.com/antnardo/pychimie) | (hors pypi) | Thermochimie des équilibres (avancement, rupture, déplacements), éléments, formules et tableau périodique en TikZ |
| [programmes-cpge](https://github.com/antnardo/programmes-cpge) | (hors pypi) | Les programmes officiels de physique-chimie des CPGE (MPSI, PCSI, MP, PC, PSI), à citer, parcourir et composer en LaTeX |
| [tpllg](https://github.com/antnardo/tpllg) | (hors pypi) | Acquisition de données en travaux pratiques, analyse de signaux |
| [sysam-sp5](https://github.com/antnardo/sysam-sp5) | (hors pypi) | Pilotes, notice et kit de programmation de la centrale Sysam SP5, et un script qui vérifie qu'un poste peut la piloter depuis Python |
