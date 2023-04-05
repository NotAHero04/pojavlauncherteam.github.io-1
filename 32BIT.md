# PojavLauncher's 32-bit support
Most of you, Android users, who are reading this now, won't be bothered by this documentation, but for the poor souls who have a 32-bit device, let's press ~~L~~ F to pay respect to them.

Before ARM transitioned into the more-powerful, more-utilizing `arm64/aarch64` architecture; everyone was using `arm/aarch32`

We're not here to give you historical information of it, but feel free to read [this documentary about the ARM platform.](https://en.m.wikipedia.org/wiki/ARM_architecture_family)

**You may encounter issues while using PojavLauncher on 32-bit devices. Here's a list of stuff that's known to be problematic:**

## RAM Allocation
* **Real 32-bit devices (32-bit hardware and firmware), can't allocate more than 768MB of RAM to PojavLauncher. This can't be changed even if the device has more free RAM.**
* Examples of real 32-bit SoCs: Qualcomm Snapdragon 801, 800, 600, 400, S4, S3, S2, S1
* **64-bit devices limited to 32-bit firmware can't allocate more than ~1000MB of RAM. As said earlier, this can't be changed.**
Please note that this limitation is device-specific, but is usually for saving storage space. Therefore, if your device has a limited storage (usually 16GB or less), it is likely to fall into this category.


## Performance
Due to limitation of 32-bit computing and the general power of 32-bit processors, Minecraft's performance is always compromised. Even with optimization mods installed, you may get big stutters even on lowest settings. Decreasing RAM Allocation may help performance in certain scenarios. Moreover, Minecraft will drop 32-bit support in a future update.
