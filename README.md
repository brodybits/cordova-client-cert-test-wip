# Cordova test app

**AUTHOR:** [@brodybits (Christopher J. Brody aka Chris Brody)](https://github.com/brodybits)

**LICENSE:** [CC0 1.0 (public domain)](https://creativecommons.org/publicdomain/zero/1.0/)

**NOTE:** This project includes JQuery (2.2.4) and Bootstrap (3.3.6) under the MIT license. Otherwise there is no code copied from other sources.

**IMPORTANT:** Whitelist and intent items are omitted from this test app.

**NOTICE:** This test does not work on macOS ("osx") since it is not supported by `cordova-plugin-dialogs`.

## Dependencies

- Bootstrap (3.3.6) - included (MIT license)
- JQuery (2.2.4) - included (MIT license)
- `cordova-plugin-dialogs` - specified in `config.xml`

NOTE: `cordova-plugin-dialogs` was added using the `--save` flag to ensure that this plugin would be automatically installed. It is recommended to use the `--save` flags to add any other plugins rather than adding such plugins to git.

## To add another plugin

```shell
cordova plugin add my-plugin-id --save
```

## How to run

**Step 1:** Add the desired platform(s), for example:

```shell
cordova platform add android
```

**Step 2 (optional):** Do `cordova prepare` (may not be necessary but good to be on the safe side):

```shell
cordova prepare
```

**Step 3:** Run it on your mobile emulator or device, for example:

```shell
cordova run android
```

## Functionality

- Native alert dialog test
