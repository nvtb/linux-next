Tegra baseline test results for next-20160202


Here are some basic Tegra test results for Linux next-20160202.
Logs and other details at:

    https://nvtb.github.io//linux-next/test_next-20160202/20160201204533/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 2/ 2): qemu-vexpress64, tegra210-p2371-0000

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_next-20160202
Test-Serial: 20160201204533
Commit-ID: 65df5e93888e0b22cfd6eaa493e5d0a921a51303
Test-Target-Board-Count: 5
Test-Boot-Count: 9
