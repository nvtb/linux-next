Tegra baseline test results for next-20170816


Here are some basic Tegra test results for Linux next-20170816.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170816/20170815223034/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big

Boot to userspace: tegra_defconfig:
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big

PM: System suspend: tegra_defconfig:
    FAIL: ( 4/ 5): tegra124-jetson-tk1, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver
    Pass: ( 1/ 5): tegra114-dalmore-a04


-------------------------------------------------------------
Branch: test_next-20170816
Test-Serial: 20170815223034
Commit-ID: 5d51332f20b270812376cf8751987e283f30de4a
Test-Target-Board-Count: 9
Test-Boot-Count: 14
