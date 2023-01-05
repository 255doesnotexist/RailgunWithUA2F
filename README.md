# Project Railgun ([中文介绍](README_zh.md))

A **railgun** for your (wireless) router(s).

***

### Usage

Go to release or Actions CI page. Use at your discretion.

***

### Supported Devices

Currently supported & Tested

|Architecture|Device|
|-|-|
|x86_64|generic (EFI boot only)|
|ipq40xx|[P&W R619AC](https://openwrt.org/toh/p_w/r619ac)|
|ramips/mt7621|[Phicomm K2P](https://openwrt.org/toh/phicomm/k2p_ke2p)|

Currently supported but untested

|Architecture|Device|
|-|-|
|ramips/mt7621|[newifi 3 / newifi D2](https://openwrt.org/toh/lenovo/newifi_d2)|

I don't have the device on hand right ATM.

***

### Additional Info

|Architecture|LuCI/LAN default IP|Username|Password|
|-|-|-|-|
|x86_64|`10.0.0.1`|`root`|`password`|
|ipq40xx|`10.0.0.1`|`root`|`password`|
|ramips/mt7621|`192.168.2.1`|`root`|`password`|

Since I daily drive this firmware as well, it might contain some dirty & ugly hacks. If you feel uncomfortable about this, do not use this firmware.

***

### If anything goes wrong...

If you think there's something wrong in my builds, feel free to create an [issue](https://github.com/KevinMX/Railgun/issues/new/choose). No annoying templates needed. Just remember to leave enough information (how to reproduce, necessary logs, etc) here. Nobody like guess your problem and come up with a solution out of no where :)

If you think the issue is from upstream projects, please open issues there.

### Credits

[P3TERX](https://p3terx.com)/[Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)

[Lean's LEDE source](https://github.com/coolsnowwolf/lede)

[padavanonly's ImmortalWrt source](https://github.com/padavanonly/immortalwrt)

[small-package](https://github.com/kenzok8/small-package)

[openwrt-mos](https://github.com/QiuSimons/openwrt-mos)

[GitHub Actions CI](https://github.com/features/actions)

[237176256 @ right.com.cn](https://www.right.com.cn/forum/space-uid-364126.html) a.k.a [MeIsReallyBa](https://github.com/MeIsReallyBa) (for guiding me enabling 802.11 k/v/r support for MT7615)

And more...

***

### License

[WTFNMF](https://github.com/adversary-org/wtfnmf) © [**Kevin.MX**](https://mary.kevinmx.top)
