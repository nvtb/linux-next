Tegra baseline test results for next-20160215


Here are some basic Tegra test results for Linux next-20160215.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160215/20160214221533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1
    Pass: ( 2/ 4): tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1
    Pass: ( 2/ 4): tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160215
Test-Serial: 20160214221533
Commit-ID: 2625f908fc0cbd7e40483217772888529ecbdfd1
Test-Target-Board-Count: 5
Test-Boot-Count: 9
