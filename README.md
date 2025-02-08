# Samsung Galaxy Tab A 10.1" 2019 LTE version (SM-T515)
This is just an experimental device tree, forked from other.
This might not successfully working to bring ARMv8-A, because from the factory, this tablet runs with arm32_binder64 a.k.a 64 bit SoC/CPU but run on 32 bit OS.
And this lacking the common files for supporting both the LTE (SM-T515) and the WiFi only version (SM-T510), help are greatly appreciated because I really need to make a vendor partition image to make arm64 GSI working on this tablet.

I might build the half-baked common files cuz I founded out Samsung Galaxy A40 (SM-A405FM) has some identical hardware, but definitely will not guaranteed working.
I have no skill about this thing so I only learn by observing the existing ones.
