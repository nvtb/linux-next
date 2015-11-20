Tegra baseline test results for next-20151120


Here are some basic Tegra test results for Linux next-20151120.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151120/20151120091534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151120
Test-Serial: 20151120091534
Commit-ID: a78de01cfa6e8c9b6ba8d1479fed4984334e2cda
Test-Target-Board-Count: 5
Test-Boot-Count: 9
