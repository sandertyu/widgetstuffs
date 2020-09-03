# What is this?

Repo for cataloging the behavior of widgets in thebelab, libretexts, and on jupyterhub. Reference to [this issue](https://github.com/LibreTexts/metalc/issues/136#issue-575899944). 

# How to use

Use `python3 -m http.server` and navigate to localhost:8000 to see the thebelab results. Change the url to the different html pages to view them.

# Checklist

|Widget|Thebelab|JupyterHub|Libretexts|
|-|-|-|-|
|ipympl|Works properly|Works properly|Works properly|
|ipyleaflet|Works properly|Works properly|Displays, but cells cannot communicate as seen in heatmap example (probably true in general and is a limitation of current CKeditor plugin)|
|pythreejs|`Uncaught (in promise) TypeError: Cannot read property 'connectToComm' of undefined`|Works properly|`Uncaught (in promise) TypeError: Cannot read property 'connectToComm' of undefined`|
|ipywidgets|`interact()` does not display the widget. Some widgets work on their own (BoundedIntText), and others do not (IntSlider).|Works Properly|`interact()` does not display the widget, same error as thebelab|
|bqplot|does not render full buttons but draws plot. probably needs some script that is included on libretexts but not here|No output except error displaying. `Error: Module bqplot, semver range ^0.5.14 is not registered as a widget module` in console|Displays plot and interactive buttons, seems to work properly|
|ipyvolume|binder build errors out, cannot even view using official [binder example](https://mybinder.org/v2/gh/maartenbreddels/ipyvolume/master?filepath=notebooks/simple.ipynb)|ipyvolume not installed|ipyvolume not installed|
|nglview|-|-|-|
|ipycytoscape|-|-|-|

# Screenshots

(to do)

