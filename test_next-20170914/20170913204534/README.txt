Tegra baseline test results for next-20170914


Here are some basic Tegra test results for Linux next-20170914.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20170914/20170913204534/


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
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 3/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra124-nyan-big, tegra20-trimslice

PM: System suspend: tegra_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice


-------------------------------------------------------------
Branch: test_next-20170914
Test-Serial: 20170913204534
Commit-ID: 31fc38c476237a405651de3faf5d3e5984c46f12
Test-Target-Board-Count: 9
Test-Boot-Count: 14
