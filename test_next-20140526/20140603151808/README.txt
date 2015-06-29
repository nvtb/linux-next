Tegra baseline test results for next-20140526


Here are some basic Tegra test results for Linux next-20140526.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20140526/20140603151808/


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
    FAIL: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    Pass: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    FAIL: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20140526
Test-Serial: 20140603151808
Commit-ID: 531a533a5118b6dc809e141199b7c978e9edf066
Test-Target-Board-Count: 2
Test-Boot-Count: 10
