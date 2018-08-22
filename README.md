# elm-spa-min-example

Minimal SPA example in Elm 0.19

npm installer doesn't work yet, so need to install binaries manually.
Here's how to do it on Linux:

``` bash
$ npm -g uninstall elm
$ wget "https://github.com/elm/compiler/releases/download/0.19.0/binaries-for-linux.tar.gz"
$ tar xzf binaries-for-linux.tar.gz
$ mv elm /usr/local/bin/
```

No clone, compile and run

``` bash
$ git clone git@github.com:nivertech/elm-spa-min-example.git

$ cd elm-spa-min-example

$ elm make src/Main.elm --debug
Dependencies loaded from local cache.
Dependencies ready!                
Success! Compiled 1 module.                                          

$ elm reactor
Go to <http://localhost:8000> to see your project dashboard.

```
