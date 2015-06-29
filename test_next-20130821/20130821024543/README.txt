Tegra baseline test results for next-20130821


Here are some basic Tegra test results for Linux next-20130821.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130821/20130821024543/


Test summary
------------

Build: zImage:
    Pass: ( 8/ 8): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra30_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
		   tegra_defconfig%tegra114_mergeconfig,
		   multi_v7_defconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

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
Branch: test_next-20130821
Test-Serial: 20130821024543
Commit-ID: 2d55880c40a3ac145ed9175d3bbdf11b80eaf861
Test-Target-Board-Count: 2
Test-Boot-Count: 10
