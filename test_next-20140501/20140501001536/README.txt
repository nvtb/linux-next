Tegra baseline test results for next-20140501


Here are some basic Tegra test results for Linux next-20140501.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20140501/20140501001536/


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
    FAIL: ( 1/ 2): tegra114-dalmore-a04
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 2): tegra114-dalmore-a04
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 1/ 2): tegra114-dalmore-a04
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20140501
Test-Serial: 20140501001536
Commit-ID: 77c3e11c26b0bc2550afd0d3147bcdef7b5f5019
Test-Target-Board-Count: 2
Test-Boot-Count: 10
