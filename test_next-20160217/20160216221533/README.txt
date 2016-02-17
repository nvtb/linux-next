Tegra baseline test results for next-20160217


Here are some basic Tegra test results for Linux next-20160217.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160217/20160216221533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160217
Test-Serial: 20160216221533
Commit-ID: b3ebd75cbc2a4833a52351c74e48f9b5e9368fd7
Test-Target-Board-Count: 5
Test-Boot-Count: 9
