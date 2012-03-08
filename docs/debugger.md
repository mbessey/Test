How the Debugger works (high level)

The Ares debugger works via sending commands to the debug target using the Chrome Remote Debugging protocol. The debugger protocol supports DOM inspection, breakpoints, variable inspection, and code evaluation. On the debuggee's end, Chrome opens up a port that the debugger 

# Debugging in the browser #
When debugging Enyo apps running in the Chrome desktop browser, these commands are sent via the ChromeDebug component.

# On-device debugging (webOS) #
When debugging on-device commands are sent via the DeviceDebug component, which communicates with the device via NovaCom port forwarding.

# additional debug connectors #
For on-device debugging on Android devices running Chrome for Android, adb can be used to set up port forwarding in a similar manner to the way we do things on webOS
