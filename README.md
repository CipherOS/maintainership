# Welcome to the CipherOS maintainership requirements

The use of “MUST”, "MUST NOT" and “SHOULD” is per the IETF standard defined in RFC2119.

## Device requirements:
* Your Cipher build MUST be stable
* All hardware features MUST work.
* Selinux MUST be enforcing
* Your kernel MUST NOT include any kind of overclocking/underclocking.
* Your kernel SHOULD be upstreamed to the latest android common kernel version
* Your device MUST use an ARM 64-bit software base. ARM 32-bit devices are no longer supported from our side.
* Your device MUST be using a kernel 4.4 base with eBPF and binder backports, or newer versions of the Linux kernel.
* Your device MUST NOT use custom fingerprints (ie, Pixel fingerprints).
* Your device MUST NOT include any magisk module integration
* Your device SHOULD have working IMS (ie, VoLTE/VoWiFi must work). (exception allowed for Exynos & Legacy MediaTek Devices)

## Maintainer requirements:
* You MUST have a proper git knowledge
* You MUST release one unofficial build before
* You MUST release each month an update before the 20th (exceptions fine)

## Tree requirements:
* Your trees MUST have a clean commit history
* Your commits MUST be properly named
* You MUST work on your trees. We don't want to see just a bringup commit

<br />
If you fulfill all these requirements open an issue in this repo
