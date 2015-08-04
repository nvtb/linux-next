Tegra baseline test results for next-20150804


Here are some basic Tegra test results for Linux next-20150804.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150804/20150803224533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150804
Test-Serial: 20150803224533
Commit-ID: d7f6af17963d3b52198d59f68a82a1991e65bf87
Test-Target-Board-Count: 5
Test-Boot-Count: 9
