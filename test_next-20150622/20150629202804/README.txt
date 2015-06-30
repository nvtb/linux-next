Tegra baseline test results for next-20150622


Here are some basic Tegra test results for Linux next-20150622.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150622/20150629202804/


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
    FAIL: ( 1/ 4): tegra124-jetson-tk1
    Pass: ( 3/ 4): tegra114-dalmore-a04, tegra20-trimslice,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150622
Test-Serial: 20150629202804
Commit-ID: c9d047c4ac9b380fb97ad9bd8b066782557dc65b
Test-Target-Board-Count: 5
Test-Boot-Count: 9
