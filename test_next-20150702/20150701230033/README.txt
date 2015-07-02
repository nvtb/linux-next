Tegra baseline test results for next-20150702


Here are some basic Tegra test results for Linux next-20150702.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20150702/20150701230033/


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
Branch: test_next-20150702
Test-Serial: 20150701230033
Commit-ID: c8a9ad223cf2d17382df7bf1c0488e7675a961e8
Test-Target-Board-Count: 5
Test-Boot-Count: 9
