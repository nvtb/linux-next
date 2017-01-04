Tegra baseline test results for next-20170104


Here are some basic Tegra test results for Linux next-20170104.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170104/20170103194534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20170104
Test-Serial: 20170103194534
Commit-ID: d7ebc8e412aec3cb259b39600bc30818bfde74ba
Test-Target-Board-Count: 9
Test-Boot-Count: 14
