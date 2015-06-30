Tegra baseline test results for next-20150618


Here are some basic Tegra test results for Linux next-20150618.
Logs and other details at:

    https://raw.githubusercontent.com/nvtb/linux-next/tree/master/test_next-20150618/20150629192144/


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
Branch: test_next-20150618
Test-Serial: 20150629192144
Commit-ID: 5877c04431a6bc0021e6c37b36c32201c8f0b4da
Test-Target-Board-Count: 5
Test-Boot-Count: 9
