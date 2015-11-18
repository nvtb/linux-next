Tegra baseline test results for next-20151118


Here are some basic Tegra test results for Linux next-20151118.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151118/20151117194534/


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
Branch: test_next-20151118
Test-Serial: 20151117194534
Commit-ID: d8a331a455872f9f0c57ef16ffa34c7a9e1e76e8
Test-Target-Board-Count: 5
Test-Boot-Count: 9
