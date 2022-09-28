# QTS5-Kernel-Module
Some compiled kernel modules for Qnap QTS 5. Modules are not being tested, vmxnet3.ko confirmed works, try at your own risk.



open-vm-tools added for QTS5, only support ESXi, start up script needs to be added or call /etc/init.d/open-vm-tools start in your own start up script.

If started after system boot, then host name may not able to be displayed, however shutdown function should work.
