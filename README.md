# Fake Speedtest

Fake your internet speed on macOS and troll your friends.

This app is for **macOS only**. It will not run on Windows or Linux.

> ⚠️ Compatibility  
> This app has been **only tested on macOS 26.1**, and **no versions before or after**.  
> If you are using a different macOS version, it might not work properly or might behave differently. No promises outside 26.1.

## Gatekeeper warning

Because the app is not notarized, macOS Gatekeeper will probably block it the first time you open it.

If that happens:

Run this: `xattr -dr com.apple.quarantine /Applications/Speedtest.app`

## Secret settings

You can configure the fake speeds so the results look realistic or completely cooked.

In the app menu bar, go to:

**Edit > Services > Uninstall > SECRET**

There you can:

- Set the **minimum Mbps**
- Set the **maximum Mbps**

The app will use values in that range to generate fake speed test results.  
Good for trolling your friends and pretending your internet is either god tier or held together with duct tape.



## License

Fake Speedtest is licensed under the Fake Speedtest License.  
Free to use and redistribute, credit required for redistribution.  
See `LICENSE` for full details.
