Tegra baseline test results for next-20171018


Here are some basic Tegra test results for Linux next-20171018.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20171018/20171018173035/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    FAIL: ( 2/ 3): tegra132-norrin, tegra210-p2371-0000
    Pass: ( 1/ 3): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big
    Pass: ( 2/ 5): tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big
    Pass: ( 2/ 5): tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big
    Pass: ( 2/ 5): tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big
    Pass: ( 2/ 5): tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20171018
Test-Serial: 20171018173035
Commit-ID: 36ef71cae353f88fd6e095e2aaa3e5953af1685d
Test-Target-Board-Count: 9
Test-Boot-Count: 14
