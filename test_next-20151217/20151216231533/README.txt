Tegra baseline test results for next-20151217


Here are some basic Tegra test results for Linux next-20151217.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151217/20151216231533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151217
Test-Serial: 20151216231533
Commit-ID: 040e3da8df803ce59db03a76dd3e18f1fae2c5fc
Test-Target-Board-Count: 5
Test-Boot-Count: 9
