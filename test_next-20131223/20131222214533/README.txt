Tegra baseline test results for next-20131223


Here are some basic Tegra test results for Linux next-20131223.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20131223/20131222214533/


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
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-headless

Boot to userspace: tegra_defconfig%tegra20,30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30,114_mergeconfig:
    FAIL: ( 1/ 2): tegra114-dalmore-headless
    Pass: ( 1/ 2): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra30_mergeconfig:
    Pass: ( 1/ 1): tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20131223
Test-Serial: 20131222214533
Commit-ID: b20898a4a0a23a491fa74e278da71bf9082c57e5
Test-Target-Board-Count: 2
Test-Boot-Count: 10
