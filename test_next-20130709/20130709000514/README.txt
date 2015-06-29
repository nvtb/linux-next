Tegra baseline test results for next-20130709


Here are some basic Tegra test results for Linux next-20130709.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130709/20130709000514/


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
Branch: test_next-20130709
Test-Serial: 20130709000514
Commit-ID: 3cb1e202c30af402226f94edec3d3f714d7beeed
Test-Target-Board-Count: 2
Test-Boot-Count: 4
