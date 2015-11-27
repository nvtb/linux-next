Tegra baseline test results for next-20151127


Here are some basic Tegra test results for Linux next-20151127.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151127/20151126220033/


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
Branch: test_next-20151127
Test-Serial: 20151126220033
Commit-ID: 0dc00719ee740f4b9d6589371d37aff6f9840249
Test-Target-Board-Count: 5
Test-Boot-Count: 9
