Tegra baseline test results for next-20141106


Here are some basic Tegra test results for Linux next-20141106.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20141106/20141106011533/


Test summary
------------

Build: zImage:
    FAIL: ( 8/ 9): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra30_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
		   tegra_defconfig%tegra124_mergeconfig,
		   tegra_defconfig%tegra114_mergeconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig
    Pass: ( 1/ 9): multi_v7_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra124_mergeconfig:
    FAIL: ( 1/ 1): tegra124-jetson-tk1

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20141106
Test-Serial: 20141106011533
Commit-ID: 5579b4b0f01b0e8a04201a7e05773066ef9909ac
Test-Target-Board-Count: 3
Test-Boot-Count: 13
