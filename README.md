# AXU2CGB
This repository will contain my work on AXU2CGB board with Xilinx Zynq Ultrascale+ FPGA.

1- Note for future, if FPGA manager is active in petalinux-config, then boot.bin will not contain FPGA code anymore, and you need to program FPGA manually :|

2- If you want to use JTAG mode, all the switches has to be ON (ON based on the label on the switch)!

Generate WKS file:

petalinux-package --wic --wks wksfile.wks --bootfiles "BOOT.BIN image.ub boot.scr" --rootfs-file "rootfs.tar.gz"
