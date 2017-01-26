Slide decks  produced from a notebook styled as slides:

- `View -> Cell Toolbar -> Slideshow`, and then `jupyter nbconvert slideTest.ipynb --to slides`

To view the slides from the notebook:

- `jupyter nbconvert slideTest.ipynb --to slides --post serve`, or
- `jupyter nbconvert slideTest.ipynb --to slides && python -m SimpleHTTPServer 8000` #then go to localhost:8000 in browser
