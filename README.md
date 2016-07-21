# ocaml-cordova-local-notifications

Binding to
[cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)

## cordova-plugin-local-notifications ?

```
This plugin implements local notifications on an Android or Apple device.
```

Source: [cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)

## Repository branches and tags

We are migrating bindings from
[js_of_ocaml](https://github.com/ocsigen/js_of_ocaml) (low level bindings) to
[gen_js_api](https://github.com/lexifi/gen_js_api) (high level bindings).

The gen_js_api binding allows to use *pure* ocaml types (you don't have to use
the ## syntax from js_of_ocaml or Js.string type but only # and string type).

The js_of_ocaml version is available in the branch
[*js_of_ocaml*](https://github.com/dannywillems/ocaml-cordova-plugin-file/tree/js_of_ocaml)
but we **recommend** to use the gen_js_api version which is the master branch.

## How to install and compile your project by using this plugin ?

Don't forget to switch to a compiler **>= 4.03.0**.
```Shell
opam switch 4.03.0
```

You can use opam by pinning the repository with
```Shell
opam pin add cordova-plugin-file https://github.com/dannywillems/ocaml-cordova-plugin-local-notifications.git
```

and to compile your project, use
```Shell
ocamlfind ocamlc -c -o [output_file] -package gen_js_api -package ocaml-cordova-plugin-file [...] -linkpkg [other arguments]
```

Don't forget to install the cordova plugin file with
```Shell
cordova plugin add https://github.com/katzer/cordova-plugin-local-notifications.git
```

## How to use ?

See the official documentation
[cordova-plugin-local-notifications](https://github.com/katzer/cordova-plugin-local-notifications)
