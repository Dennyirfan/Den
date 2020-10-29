To enable WRITE_SECURE_SETTINGS permission please follow the instructions below:

For Windows:
1. Download the ZIP file
2. Enable USB Debugging
3. Run the script
4. Done

For Linux:
You can download ADB [here](https://developer.android.com/studio/releases/platform-tools), open the terminal in the unzipped folder, connect your phone, then run the command `adb shell pm grant com.thewizrd.simplewear android.permission.WRITE_SECURE_SETTINGS`. Finally, restart the app.