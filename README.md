# What is this?

Repo for cataloging the behavior of widgets in thebelab, libretexts, and on jupyterhub. Reference to [this issue](https://github.com/LibreTexts/metalc/issues/136#issue-575899944). 

# How to use

Use `python3 -m http.server` and navigate to localhost:8000 to see the thebelab results. Change the url to the different html pages to view them.

# Checklist

|Widget|Thebelab|JupyterHub|Libretexts|
|-|-|-|-|
|ipympl|Plots need `require.min.js` script to load, and `Font Awesome 5` for the interactive buttons|Works properly|Works properly|
|ipyleaflet|Works properly|Works properly|Displays, but cells cannot communicate as seen in heatmap example|
|pythreejs|-|-|-|
|ipywidgets|-|-|-|
|bqplot|-|-|-|
|ipyvolume|-|-|-|
|nglview|-|-|-|
|ipycytoscape|-|-|-|

# Screenshots

(to do)

