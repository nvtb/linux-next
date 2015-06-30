Tegra baseline test results for next-20150619


Here are some basic Tegra test results for Linux next-20150619.
Logs and other details at:

    https://raw.githubusercontent.com/nvtb/linux-next/tree/master/test_next-20150619/20150629193033/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150619
Test-Serial: 20150629193033
Commit-ID: c1ce6ea24e13fcdb61c75d7bb24377d11478b3c4
Test-Target-Board-Count: 5
Test-Boot-Count: 9
