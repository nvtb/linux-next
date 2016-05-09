Tegra baseline test results for next-20160509


Here are some basic Tegra test results for Linux next-20160509.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160509/20160508233033/


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
    FAIL: ( 2/ 4): tegra114-dalmore-a04, tegra30-beaver
    Pass: ( 2/ 4): tegra124-jetson-tk1, tegra20-trimslice

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 4): tegra114-dalmore-a04
    Pass: ( 3/ 4): tegra124-jetson-tk1, tegra20-trimslice,
		   tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160509
Test-Serial: 20160508233033
Commit-ID: 2f91cb029bf43b17f52a76661d555a5147bfd806
Test-Target-Board-Count: 5
Test-Boot-Count: 9
