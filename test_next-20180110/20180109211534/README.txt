Tegra baseline test results for next-20180110


Here are some basic Tegra test results for Linux next-20180110.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20180110/20180109211534/


Test summary
------------

Build: zImage:
    Pass: ( 3/ 3): multi_v7_defconfig, tegra_defconfig,
		   tegra_defconfig%tegra-fw

Build: Image:
    Pass: ( 3/ 3): defconfig, defconfig%jetson-tx2,
		   defconfig%jetson-tx1

Boot to userspace: defconfig:
    FAIL: ( 2/ 4): qemu-vexpress64, tegra210-p2371-0000
    Pass: ( 2/ 4): tegra132-norrin, tegra210-smaug

Boot to userspace: defconfig%jetson-tx1:
    FAIL: ( 2/ 2): tegra210-p2371-0000, tegra210-p2371-2180

Boot to userspace: defconfig%jetson-tx2:
    WARN: ( 1/ 1): tegra186-p2771-0000

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra-fw:
    FAIL: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig%tegra-fw:
    FAIL: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20180110
Test-Serial: 20180109211534
Commit-ID: b4464bcab38d3f7fe995a7cb960eeac6889bec08
Test-Target-Board-Count: 9
Test-Boot-Count: 14
