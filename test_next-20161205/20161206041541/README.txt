Tegra baseline test results for next-20161205


Here are some basic Tegra test results for Linux next-20161205.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20161205/20161206041541/


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
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20161205
Test-Serial: 20161206041541
Commit-ID: cef87e91155479753a3052e95d0aa2fdf8d46dc0
Test-Target-Board-Count: 9
Test-Boot-Count: 14
