Tegra baseline test results for next-20131023


Here are some basic Tegra test results for Linux next-20131023.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20131023/20131023081944/


Test summary
------------

Build: zImage:
    FAIL: ( 5/ 8): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
		   tegra_defconfig%tegra114_mergeconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig
    Pass: ( 3/ 8): tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra30_mergeconfig,
		   multi_v7_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20131023
Test-Serial: 20131023081944
Commit-ID: 7783be7bb0fccbe72718ee8ecd16cf5fb5657ad5
Test-Target-Board-Count: 2
Test-Boot-Count: 10
