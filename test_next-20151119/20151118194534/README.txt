Tegra baseline test results for next-20151119


Here are some basic Tegra test results for Linux next-20151119.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151119/20151118194534/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    FAIL: ( 1/ 1): defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20151119
Test-Serial: 20151118194534
Commit-ID: 4a79170ff5ccbbfa0969dcd2bef02b3ccf01e9e6
Test-Target-Board-Count: 5
Test-Boot-Count: 9
