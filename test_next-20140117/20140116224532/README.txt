Tegra baseline test results for next-20140117


Here are some basic Tegra test results for Linux next-20140117.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20140117/20140116224532/


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
    FAIL: ( 1/ 2): tegra114-dalmore-headless
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20140117
Test-Serial: 20140116224532
Commit-ID: ee8502c1320d626417b98a94e0367e9a1e269a5a
Test-Target-Board-Count: 2
Test-Boot-Count: 10
