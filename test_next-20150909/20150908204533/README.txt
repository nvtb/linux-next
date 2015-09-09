Tegra baseline test results for next-20150909


Here are some basic Tegra test results for Linux next-20150909.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150909/20150908204533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150909
Test-Serial: 20150908204533
Commit-ID: 72c9d8043fdc87832802de0b7a7129d6fc4c4c70
Test-Target-Board-Count: 5
Test-Boot-Count: 9
