Tegra baseline test results for next-20160112


Here are some basic Tegra test results for Linux next-20160112.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160112/20160112000034/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 4): tegra20-trimslice
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20160112
Test-Serial: 20160112000034
Commit-ID: d299f5e5d5dbee2c57425aeb27c362c44b8d4cd5
Test-Target-Board-Count: 5
Test-Boot-Count: 9
