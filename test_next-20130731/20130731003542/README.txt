Tegra baseline test results for next-20130731


Here are some basic Tegra test results for Linux next-20130731.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130731/20130731003542/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 8): tegra_defconfig%tegra114_mergeconfig
    Pass: ( 7/ 8): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra30_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
		   multi_v7_defconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20130731
Test-Serial: 20130731003542
Commit-ID: c1462f7e87b880662db029615ea5bd8d9337261d
Test-Target-Board-Count: 2
Test-Boot-Count: 10
