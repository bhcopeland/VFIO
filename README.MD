PCI Passthrough.

Specs:

Asus deluxe x99
Intel 6850K

Host GPU: R9 Fury
Guest GPU: GTX 970

Host OS: Arch Linux

QEMU

nvram = [
	"/usr/share/ovmf/ovmf_code_x64.bin:/usr/share/ovmf/ovmf_vars_x64.bin"
]

Needs to be added for OVMF UEFI support


