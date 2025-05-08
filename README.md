# Limbo Emulator (QEMU) for Android
(Unofficial Refresh Fork)
#
# For the official APK Downloads, Guides, and Help visit either:
https://virtualmachinery.weebly.com
or
https://github.com/limboemu/limbo

Limbo is a QEMU-based emulator for Android supports emulation for these architectures:
	x86/x86_64
	ARM/ARM64
	PowerPC/PowerPC64
	Sparc

For developers read file README.developers for instructions on how to compile on your own
	and other useful information.


This specific fork is made to remain up to date with the latest QEMU, incorporate more features and options.

TODO:

1. ```Introduce native/builtin SPICE client, as an addition to the other display options. (Alongside SDL, and VNC.)```

2. ```Merge all QEMU system emulators into one option menu, to select from. (Being able to choose what architecture you want to emulate, in-app, instead of it being per-app.) (Parameter options will change to reflect and remain compatible with the selected architecture.)```

3. ```Renovate and refresh the UI. (Turn RAM amount, CPU core amount, from dropdown menu, to slider, with a textbot for manual selection.)```

4. ```Automatically turn existing QEMU params that are placed into extra QEMU params on bottom, into changes that reflect the command line options pasted/manually written.```

5. ```Detect HID peripherals, and capture them, instead of echoing their position from surface to app.```

6. ```Introduce support for MIPS architecture emulation.```

(Basically match featureset of UTM, and Virt-Manager.)

(References)
https://virt-manager.org/
https://mac.getutm.app/
https://github.com/limboemu/limbo
