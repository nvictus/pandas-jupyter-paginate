# pandas-jupyter-paginate

Forked from: https://gist.github.com/nokados/e8f0a64b55099f2f07a50f2b090c91c7 by [@nokados](https://github.com/nokados)

Changes
* Added slider control to scroll through pages of really large dataframes.
* Reduce flicker by making events trigger widget element updates instead of
  clearing output and re-rendering.
* Add support for dataframe CSS styling.
* Register custom pandas accessor
