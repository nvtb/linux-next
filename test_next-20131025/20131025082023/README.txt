Tegra baseline test results for next-20131025


Here are some basic Tegra test results for Linux next-20131025.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20131025/20131025082023/


Test summary
------------

Build: zImage:
    FAIL: ( 5/ 8): tegra_defconfig%tegra20,114_mergeconfig,
		   tegra_defconfig%tegra30,114_mergeconfig,
		   tegra_defconfig%tegra114_mergeconfig,
		   tegra_defconfig%tegra20_mergeconfig, tegra_defconfig
    Pass: ( 3/ 8): tegra_defconfig%tegra30_mergeconfig,
		   tegra_defconfig%tegra20,30_mergeconfig,
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
    Pass: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20131025
Test-Serial: 20131025082023
Commit-ID: 9e11bce4d7065aa826a953936149e182e018a3df
Test-Target-Board-Count: 2
Test-Boot-Count: 10
