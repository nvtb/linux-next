Tegra baseline test results for next-20130712


Here are some basic Tegra test results for Linux next-20130712.
Logs and other details at:

    http://nvt.pwsan.com/experimental/testlogs/test_next-20130712/20130711213513/


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
Branch: test_next-20130712
Test-Serial: 20130711213513
Commit-ID: 3e91c07702ebc2e49c4bea72ee62addb4693c3e0
Test-Target-Board-Count: 2
Test-Boot-Count: 4
