Tegra baseline test results for next-20160728


Here are some basic Tegra test results for Linux next-20160728.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160728/20160727223034/


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
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big

Boot to userspace: tegra_defconfig:
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver
    Pass: ( 1/ 5): tegra124-nyan-big

PM: System suspend: tegra_defconfig:
    FAIL: ( 3/ 5): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver
    Pass: ( 2/ 5): tegra114-dalmore-a04, tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20160728
Test-Serial: 20160727223034
Commit-ID: d4e661a48572b90ab727149e2f2ec087380a573b
Test-Target-Board-Count: 9
Test-Boot-Count: 14
