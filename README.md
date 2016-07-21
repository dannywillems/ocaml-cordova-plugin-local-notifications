# ocaml-cordova-local-notifications

Binding to
[cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)

## cordova-plugin-local-notifications ?

```
This plugin implements local notifications on an Android or Apple device.
```

Source: [cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)

## How to install and compile your project by using this plugin ?

Don't forget to switch to a compiler **>= 4.03.0**.
```Shell
opam switch 4.03.0
```

You can use opam by pinning the repository with
```Shell
opam pin add cordova-plugin-local-notifications https://github.com/dannywillems/ocaml-cordova-plugin-local-notifications.git
```

and to compile your project, use
```Shell
ocamlfind ocamlc -c -o [output_file] -package gen_js_api -package ocaml-cordova-plugin-local-notifications [...] -linkpkg [other arguments]
```

Don't forget to install the cordova local notifications plugin with
```Shell
cordova plugin add https://github.com/katzer/cordova-plugin-local-notifications.git
```

## How to use ?

See the official documentation
[cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)
