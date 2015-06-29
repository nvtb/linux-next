Tegra baseline test results for next-20130708


Here are some basic Tegra test results for Linux next-20130708.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130708/20130707230516/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): multi_v7_defconfig
    Pass: ( 1/ 2): tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-headless, tegra30-beaver



-------------------------------------------------------------
Branch: test_next-20130708
Test-Serial: 20130707230516
Commit-ID: 43ab7daf16ce9dc89ae2e1e8ecaca06e4a9a7cd1
Test-Target-Board-Count: 2
Test-Boot-Count: 4
