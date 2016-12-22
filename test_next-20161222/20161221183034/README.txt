Tegra baseline test results for next-20161222


Here are some basic Tegra test results for Linux next-20161222.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20161222/20161221183034/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra20-trimslice
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20161222
Test-Serial: 20161221183034
Commit-ID: 49358776a0a64bb2ea6301d12381659a8e3388ae
Test-Target-Board-Count: 9
Test-Boot-Count: 14
