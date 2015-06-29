Tegra baseline test results for next-20130702


Here are some basic Tegra test results for Linux next-20130702.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130702/20130702040300/


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
Branch: test_next-20130702
Test-Serial: 20130702040300
Commit-ID: e8e1f4c8a798998aad598698b3dd44a95ab80573
Test-Target-Board-Count: 2
Test-Boot-Count: 4
