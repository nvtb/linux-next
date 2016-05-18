Tegra baseline test results for next-20160518


Here are some basic Tegra test results for Linux next-20160518.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160518/20160517220034/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 3/ 3): qemu-vexpress64, tegra210-p2371-0000, tegra210-smaug

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra30-beaver
    Pass: ( 2/ 4): tegra124-jetson-tk1, tegra20-trimslice

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160518
Test-Serial: 20160517220034
Commit-ID: 621a2a0fb6688af5dce47d60a6d4b5a19ae2c2e4
Test-Target-Board-Count: 5
Test-Boot-Count: 9
