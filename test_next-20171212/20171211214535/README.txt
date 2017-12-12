Tegra baseline test results for next-20171212


Here are some basic Tegra test results for Linux next-20171212.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20171212/20171211214535/


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
    Pass: ( 1/ 1): tegra186-p2771-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra-fw:
    FAIL: ( 1/ 2): tegra124-jetson-tk1
    Pass: ( 1/ 2): tegra124-nyan-big

PM: System suspend: multi_v7_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig%tegra-fw:
    Pass: ( 2/ 2): tegra124-jetson-tk1, tegra124-nyan-big


-------------------------------------------------------------
Branch: test_next-20171212
Test-Serial: 20171211214535
Commit-ID: d20787938ddbfd38fa25b3b66068d0f8b5cfc45e
Test-Target-Board-Count: 9
Test-Boot-Count: 14
