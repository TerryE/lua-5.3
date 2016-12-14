## Lua 5.3 for NodeMCU architectures ESP8266 and ESP32

This repo is based on:

-  The [lua.org downloads](https://www.lua.org/download.html) 5.3.3 distro: lua-5.3.3.tar.gz  2016-05-30, 288K  \(md5:703f75caa4fdf4a911c1a72e67a27498\)
-  The [lua.org Test Suites](https://www.lua.org/tests/) 5.3.3-tests distro: lua-5.3.3-tests.tar.gz 2016-05-30 102562  md5: \(76f4fb07f2a4970d554645ac26df86df\)

And will include a set of transformation steps to migrate the 5.3.3 build to the target ESP architectures.  At each stage the test suites will by used to validate the transformation steps so that each clean commit point will pass the tests.
