Tegra baseline test results for next-20170112


Here are some basic Tegra test results for Linux next-20170112.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170112/20170111201534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 2/ 5): tegra124-jetson-tk1, tegra20-trimslice
    Pass: ( 3/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-jetson-tk1
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-nyan-big,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20170112
Test-Serial: 20170111201534
Commit-ID: eec0d3d065bfcdf9cd5f56dd2a36b94d12d32297
Test-Target-Board-Count: 9
Test-Boot-Count: 14
