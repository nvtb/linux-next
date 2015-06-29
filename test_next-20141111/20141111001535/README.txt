Tegra baseline test results for next-20141111


Here are some basic Tegra test results for Linux next-20141111.
Logs and other details at:

    http://nvt.pwsan.com/experimental/linux-next/testlogs/test_next-20141111/20141111001535/


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
    FAIL: ( 2/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1
    Pass: ( 1/ 3): tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 2/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1
    Pass: ( 1/ 3): tegra30-beaver

Boot to userspace: tegra_defconfig%tegra114_mergeconfig:
    FAIL: ( 1/ 1): tegra114-dalmore-a04

Boot to userspace: tegra_defconfig%tegra124_mergeconfig:
    FAIL: ( 1/ 1): tegra124-jetson-tk1

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
Branch: test_next-20141111
Test-Serial: 20141111001535
Commit-ID: b0187bd33fba065ec736dc33085914a137d390d3
Test-Target-Board-Count: 3
Test-Boot-Count: 13
