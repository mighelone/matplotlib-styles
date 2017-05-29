# matplotlib-styles
Personal styles for matplotlib

* **tthmod** modified tth style
* **mystyle** my new style

## Install

Go to your `mpl_configdir` directory. Generally it is `~/.config/matplotlib` or `~/.matplotlib` depending on your system.

Clone the project inside `mpl_configdir`:

```
# git clone https://github.com/mighelone/matplotlib-styles.git mpl_configdir/stylelib
```

Than, you can use the style, combining one or more style:

```
>>> plt.style.use(['mystyle', 'mystyle-vega'])
```
