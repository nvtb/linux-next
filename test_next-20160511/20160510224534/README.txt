Tegra baseline test results for next-20160511


Here are some basic Tegra test results for Linux next-20160511.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160511/20160510224534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 3/ 3): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160511
Test-Serial: 20160510224534
Commit-ID: 13425f1bf7f9f28fcef53057303319d5afb907f7
Test-Target-Board-Count: 5
Test-Boot-Count: 9
