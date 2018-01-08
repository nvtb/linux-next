Tegra baseline test results for next-20180108


Here are some basic Tegra test results for Linux next-20180108.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20180108/20180107213034/


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
    WARN: ( 1/ 2): tegra210-p2371-2180
    FAIL: ( 1/ 2): tegra210-p2371-0000

Boot to userspace: defconfig%jetson-tx2:
    WARN: ( 1/ 1): tegra186-p2771-0000

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

Boot to userspace: tegra_defconfig%tegra-fw:
    FAIL: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra30-beaver
    Pass: ( 1/ 5): tegra20-trimslice

PM: System suspend: tegra_defconfig%tegra-fw:
    FAIL: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20180108
Test-Serial: 20180107213034
Commit-ID: 895c0dde398510a5b5ded60e5064c11b94bd30ca
Test-Target-Board-Count: 9
Test-Boot-Count: 14
