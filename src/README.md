IPython Notebooks
=================
This directory contains the IPython notebooks.

Start IPython in this directory with the command. If all works your browser will open with the contents shown

```
   ipython notebook
```

in the /static direcory there is a simple css file that is called at the end of each notebook to make it all look a bit more pretty.

``` python
		#  load custom css 
		from IPython.core.display import HTML
		def css_styling():
			styles = open("static\custom.css", "r").read()
			return HTML(styles)
		css_styling()
```