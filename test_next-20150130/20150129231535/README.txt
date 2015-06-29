Tegra baseline test results for next-20150130


Here are some basic Tegra test results for Linux next-20150130.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20150130/20150129231535/


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
    FAIL: ( 2/ 3): tegra114-dalmore-a04, tegra30-beaver
    Pass: ( 1/ 3): tegra124-jetson-tk1

Boot to userspace: tegra_defconfig:
    FAIL: ( 2/ 3): tegra114-dalmore-a04, tegra30-beaver
    Pass: ( 1/ 3): tegra124-jetson-tk1

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra124_mergeconfig:
    Pass: ( 1/ 1): tegra124-jetson-tk1

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20150130
Test-Serial: 20150129231535
Commit-ID: 827e3bdf1bb2401c1a1e5586eb3977d228d298b2
Test-Target-Board-Count: 3
Test-Boot-Count: 13
