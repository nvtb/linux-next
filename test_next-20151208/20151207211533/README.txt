Tegra baseline test results for next-20151208


Here are some basic Tegra test results for Linux next-20151208.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20151208/20151207211533/


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
Branch: test_next-20151208
Test-Serial: 20151207211533
Commit-ID: 856ed208dd69d03c00670db5c235d253af443440
Test-Target-Board-Count: 5
Test-Boot-Count: 9
