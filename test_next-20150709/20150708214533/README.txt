Tegra baseline test results for next-20150709


Here are some basic Tegra test results for Linux next-20150709.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150709/20150708214533/


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
Branch: test_next-20150709
Test-Serial: 20150708214533
Commit-ID: 09d87ac2ab8a70a46e5b597a4636d4eb88f2ce31
Test-Target-Board-Count: 5
Test-Boot-Count: 9
