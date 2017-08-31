Tegra baseline test results for next-20170831


Here are some basic Tegra test results for Linux next-20170831.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170831/20170831021534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

PM: System suspend: tegra_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice


-------------------------------------------------------------
Branch: test_next-20170831
Test-Serial: 20170831021534
Commit-ID: e8b684315214053f29f7f78643aefd19da342976
Test-Target-Board-Count: 9
Test-Boot-Count: 14
