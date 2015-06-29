Tegra baseline test results for next-20140723


Here are some basic Tegra test results for Linux next-20140723.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20140723/20140723023034/


Test summary
------------

Build: zImage:
    Pass: ( 9/ 9): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra30_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
		   tegra_defconfig%tegra124_mergeconfig,
		   tegra_defconfig%tegra114_mergeconfig,
		   multi_v7_defconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    Pass: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20140723
Test-Serial: 20140723023034
Commit-ID: 5eb00b037d9bb650b18b8f331bb9fb7a66559b5f
Test-Target-Board-Count: 2
Test-Boot-Count: 10
