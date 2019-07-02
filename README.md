# surf - simple webkit-based browser

Surf is a simple Web browser based on WebKit/GTK+.

### Prerequisites

In order to build surf you need GTK+ and Webkit/GTK+ header files.

In order to use the functionality of the url-bar, also install dmenu[0].

### Installing

Edit config.mk to match your local setup (surf is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install surf (if
necessary as root):

```
make clean install
```

## Running the tests

Run
```
surf [URI]
```
See the manpage for further options.

For running surf in tabbed[1] there is a script included in the distribution,
which is run like this:

```
surf-open.sh [URI]
```

## Deployment

Further invocations of the script will run surf with the specified URI in this
instance of tabbed.

[0] http://tools.suckless.org/dmenu
[1] http://tools.suckless.org/tabbed
