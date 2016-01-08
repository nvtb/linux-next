Tegra baseline test results for next-20160108


Here are some basic Tegra test results for Linux next-20160108.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160108/20160107234534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20160108
Test-Serial: 20160107234534
Commit-ID: e04c94f10a05003e5b6f2978efcc37b282483c2f
Test-Target-Board-Count: 5
Test-Boot-Count: 9
