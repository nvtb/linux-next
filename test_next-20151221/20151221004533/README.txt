Tegra baseline test results for next-20151221


Here are some basic Tegra test results for Linux next-20151221.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151221/20151221004533/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): tegra_defconfig
    Pass: ( 1/ 2): multi_v7_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151221
Test-Serial: 20151221004533
Commit-ID: 6fadd3a85f4381c065ca2accbedaa622f83697ad
Test-Target-Board-Count: 5
Test-Boot-Count: 9
