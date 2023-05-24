# NSOk

NSOk requires a rooted Android phone.

1. Install [Magisk](https://github.com/topjohnwu/Magisk/releases)
    - Disable "Enforce DenyList" in Magisk Settings
    - Tick NSO app in DenyList

2. Install [LSPosed](https://github.com/LSPosed/LSPosed/releases/tag/v1.8.6) and [Shamiko](https://github.com/LSPosed/LSPosed.github.io/releases) in Magisk

3. Install NSOk, enable it in LSPosed

4. Reboot, and open NSO app

5. NSOk is now running on the `9000` port of your phone. Forward it to your PC using adb (`adb tcp:9000 tcp:9000`), and you can access it using `http://127.0.0.1:9000/k`