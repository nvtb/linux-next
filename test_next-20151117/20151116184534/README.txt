Tegra baseline test results for next-20151117


Here are some basic Tegra test results for Linux next-20151117.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151117/20151116184534/


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
Branch: test_next-20151117
Test-Serial: 20151116184534
Commit-ID: e483c0d725bc7f806f96231a0d5ac894c70fd3aa
Test-Target-Board-Count: 5
Test-Boot-Count: 9
