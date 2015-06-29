Tegra baseline test results for next-20130703


Here are some basic Tegra test results for Linux next-20130703.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130703/20130703013518/


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
Branch: test_next-20130703
Test-Serial: 20130703013518
Commit-ID: fa1383200d289afdff2f5678eb89483daa537465
Test-Target-Board-Count: 2
Test-Boot-Count: 4
