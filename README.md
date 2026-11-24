# Head Tilt beta installation

Head Tilt is a native macOS app for headphone-based posture awareness.
This repository contains public beta downloads and installation help.

## Download and install

1. Get beta access at https://headtilt.maddynator.chatgpt.site/.
2. Extract the downloaded ZIP.
3. Quit any older copy of Head Tilt, then drag **Head Tilt.app** into **Applications**.
4. Open Head Tilt from Applications.

The current download requires an Apple silicon Mac with macOS 14 or later.
Read the release notes for headphone compatibility and known beta limitations.

## macOS security warning

**Seeing “Head Tilt Not Opened” and “Apple could not verify ‘Head Tilt’ is free of malware”?**

The current beta is ad hoc signed and has not been notarized by Apple.
This message means macOS cannot verify the app; it is not, by itself, a malware detection or a guarantee that the app is safe.

Only continue if you obtained the app through the official Head Tilt website or this repository's release page, trust the source, and are comfortable testing an unnotarized beta.
You can also wait for a signed and notarized release.

After attempting to open Head Tilt:

1. Click **Done** on the warning.
2. Open **System Settings**.
3. Select **Privacy & Security** and scroll to the **Security** section.
4. Find the message about Head Tilt and click **Open Anyway**.
5. Authenticate if prompted, then click **Open** in the confirmation.

This creates an exception for this app.
You do not need to disable Gatekeeper or run Terminal commands.
Apple documents this process at https://support.apple.com/en-us/102445.

### If Open Anyway is missing or the warning is different

- Try opening Head Tilt once more from Applications, then return to Privacy & Security.
- On a work-managed Mac, your organization may prevent this exception; contact your IT team.
- If macOS says the app **will damage your computer**, **contains malware**, or **is damaged**, do not use these steps to bypass that warning.
  Contact support with the exact message.

## First launch

1. Wear compatible headphones and connect them to this Mac.
2. In Head Tilt, click **Connect AirPods** and allow motion access when macOS asks.
3. Set a comfortable straight-ahead baseline.
4. Hold a small downward nod and click **Confirm down**.
5. Return to level, then tilt your left ear toward your shoulder and click **Confirm left**.

Use small, comfortable movements.
A Bluetooth audio connection alone does not guarantee headphone motion is available.
Complete a new calibration when switching headphones.

## Need help?

Email **verma.mayank@gmail.com** with the warning screenshot, your macOS version, and the Head Tilt build you downloaded.
Do not include passwords, serial numbers, or other sensitive information.
Reports are not sent automatically.
