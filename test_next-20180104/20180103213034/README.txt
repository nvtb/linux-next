Tegra baseline test results for next-20180104


Here are some basic Tegra test results for Linux next-20180104.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20180104/20180103213034/


Test summary
------------

Build: zImage:
    Pass: ( 3/ 3): multi_v7_defconfig, tegra_defconfig,
		   tegra_defconfig%tegra-fw

Build: Image:
    Pass: ( 3/ 3): defconfig, defconfig%jetson-tx2,
		   defconfig%jetson-tx1

Boot to userspace: defconfig:
    FAIL: ( 1/ 4): qemu-vexpress64
    Pass: ( 3/ 4): tegra132-norrin, tegra210-p2371-0000, tegra210-smaug

Boot to userspace: defconfig%jetson-tx1:
    Pass: ( 2/ 2): tegra210-p2371-0000, tegra210-p2371-2180

Boot to userspace: defconfig%jetson-tx2:
    WARN: ( 1/ 1): tegra186-p2771-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra-fw:
    Pass: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig%tegra-fw:
    Pass: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20180104
Test-Serial: 20180103213034
Commit-ID: f4286eee6c7820b308eaed97fc38ccbff9a8d0f0
Test-Target-Board-Count: 9
Test-Boot-Count: 14
