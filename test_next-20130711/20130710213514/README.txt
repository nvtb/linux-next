Tegra baseline test results for next-20130711


Here are some basic Tegra test results for Linux next-20130711.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130711/20130710213514/


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
Branch: test_next-20130711
Test-Serial: 20130710213514
Commit-ID: 0ed4402317bf2f3e579b86081ccde0fb5ad55b4b
Test-Target-Board-Count: 2
Test-Boot-Count: 4
