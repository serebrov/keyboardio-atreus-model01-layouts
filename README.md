# Layout

Atreus and Model01 layouts here are ports of my moonlander [layout](https://configure.zsa.io/moonlander/layouts/MJvlL/latest/0), but without autoshift.

# Atreus

Layouts under the [./atreus](./atreus) folder:

* 2022-12-10-Layout.json - default initial layout
* 2022-12-11-Layout.json - work in progress
* 2022-12-11-Layout-test-two-sym.json - port of my moonlander [layout](https://configure.zsa.io/moonlander/layouts/MJvlL/latest/0), but without autoshift.
* 2022-12-11-atreus-Layout-test-two-sym.json - same as above, but with two slightly different Sym layers where opposite hand produces numbers and same hand produces shifted numbers.

# Model 01

Layouts under the [./model01](./model01) folder:

* 2022-12-14-model01-default-Layout.json - default layout as I get it.
* 2022-12-14-model01-default-latest-firmware-Layout.json - default layout after firmware update.
* 2022-12-17-model01-mini-Layout.json - port of my moonlander [layout](https://configure.zsa.io/moonlander/layouts/MJvlL/latest/0), but without autoshift.
* 2022-12-17-model01-mini-oneshot-Layout.json - same as above, but with custom firmware from [Model01-oneshot_20221217202716](./Model01-oneshot_20221217202716)
with OneShot plugin enabled and DynamicMacros disabled (to free space for OneShot).

## Short Custom Firmware Guide

Download, install and configure Arduino IDE, see the [docs](https://kaleidoscope.readthedocs.io/en/latest/setup_toolchain.html#set-up-the-arduino-ide).

- Open [./Model01-oneshot_20221217202716](./Model01-oneshot_20221217202716) in  Arduino IDE.
- Change what's needed, compile (the first "Verify" button in the top panel).
- Hold the `Prog` button on keyboard (left top corner)
- Upload the firmware from Arduino IDE (the second "Upload" button)

The way it is in the code now, the layout is not erased/replaced, after flashing
the firmware, one shot features became available in Chrysalis and added one shot
mods I needed.




