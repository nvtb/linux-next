Tegra baseline test results for next-20131219


Here are some basic Tegra test results for Linux next-20131219.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20131219/20131218223033/


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
    FAIL: ( 1/ 2): tegra114-dalmore-headless
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 2): tegra114-dalmore-headless
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20131219
Test-Serial: 20131218223033
Commit-ID: 289d56f61293f12a0035b7a9c0a0c4d1f657d5c6
Test-Target-Board-Count: 2
Test-Boot-Count: 10
