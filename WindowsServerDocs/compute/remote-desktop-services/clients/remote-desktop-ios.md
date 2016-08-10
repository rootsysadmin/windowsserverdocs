---
title: Get started with Remote Desktop on iOS
ms.custom: na
ms.prod: windows-server-threshold
ms.reviewer: na
ms.suite: na
ms.technology: 
  - remote-desktop-services
ms.tgt_pltfrm: na
ms.topic: article
ms.assetid: 03ec5a3d-d3f2-4afd-9405-ae58b6ecc91c
author: lizap
manager: msswadhwa
---
# Get started with Remote Desktop on iOS

>Applies To: Windows 10, Windows 8.1, Windows Server 2012 R2, Windows Server Technical Preview

Devices running iOS 6.x and newer are supported.

Microsoft Remote Desktop Client gives you the ability to get work done from almost anywhere by providing an easy way to use your mobile device to: 

- Connect to a remote PC to access all of your apps, files, and network resources
- Access published Windows apps hosted on Microsoft Azure



## Start using the Remote Desktop client on your iOS device
Follow these steps to get started with Remote Desktop on your iOS device:

1. Download the Microsoft Remote Desktop client from [iTunes](https://itunes.apple.com/us/app/microsoft-remote-desktop/id714464092?mt=8).
2. Set up your PC to accept remote connections.
3. Create a new Remote Desktop connection or add a remote resource.

A remote desktop connection summarizes all the settings for the remote desktop you want to connect to.

Remote Resources enables access to RemoteApp programs, session-based desktops, and virtual desktops published on-premises using RemoteApp and Desktop Connections. This feature is typically available in corporate environments.

RemoteApp is also available as a cloud-based service that provides access to published applications on Microsoft Azure. For more information, visit the Azure RemoteApp landing page.

## Getting to know the Connection Center

After the Remote Desktop Client is installed, start the app, and the connection center will open. You can use the connection center to:

- Connect to a Windows PC or server
- Access on-premises work resources published using RemoteApp and Desktop Connections
- Access apps in the cloud through Azure RemoteApp
- Manage remote desktops
- Modify settings

### Create and edit Remote Desktops

A remote desktop summarizes all the settings for the remote desktop connection.

To create a remote desktop: 
1. In the Connection Center tap **+**, and then tap **Add PC or Server**.
2. Enter the following information for the remote desktop connection:
  - **PC name** – the name of the computer. This can be a Windows computer name, an Internet domain name, or an IP address. You can also append port information to the PC name (for example, **MyDesktop:3389** or **10.0.0.1:3389**).
  - **User name** – The user name to use to access the remote PC. You can use the following formats: *user_name*, *domain\user_name*, or *user_name@domain.com*. You can also specify whether to prompt for a user name and password.
3. You can also set the following additional options:
  - **Friendly name (optional)** – An easy-to-remember name for the PC you are connecting to. You can use any string, but if you do not specify a friendly name, the PC name is displayed.
  - **Gateway (optional)** – The Remote Desktop gateway that you want to use to connect to virtual desktops, RemoteApp programs, and session-based desktops on an internal corporate network. Get the information about the gateway from your system administrator.
  - **Sound** – Select the device to use for audio during your remote session. You can choose to play sound on the local devices, the remote device, or not at all.
  - **Swap mouse buttons** – Whenever a mouse gesture would send a command with the left mouse button, it sends the same command with the right mouse button instead. This is necessary if the remote PC is configured for left-handed mouse mode.
  - **Admin Mode** - Connect to an administration session on a server running Windows Server 2003 or later.
4. Tap **Save**.

Need to edit these settings? Press and hold the desktop you want to edit, and then tap the settings icon. 

To delete a remote desktop, press and hold the desktop you want to delete. Tap the **Delete** icon.

## Gateway

A Remote Desktop Gateway (RD Gateway) lets authorized users connect to a remote computer on a corporate network from anywhere on the Internet. You can create and manage your gateways using the Remote Desktop client.

To set up a new gateway:

1. In the Connection Center, tap **Settings > Gateways**. 
2. Tap **Add Remote Desktop gateway**.
3. Enter the following information:
  - **Server name** – The name of the computer you want to use as a gateway. This can be a Windows computer name, an Internet domain name, or an IP address. You can also add port information to the server name (for example: **RDGateway:443** or **10.0.0.1:443**).
  - **User name** - The user name and password to be used for the Remote Desktop gateway you are connecting to. You can also select **Use connection credentials** to use the same user name and password as those used for the remote desktop connection.

To delete a gateway:

1. In the Connection Center, tap **Settings > Gateways**.
2. Swipe a row from right to left to select the gateway.
3. Tap **Delete**.

## User management

When you connect to a desktop or remote resources, you can save the user accounts to select from again. You can manage your user accounts by using the Remote Desktop client.

To create a new user account:

1. In the Connection Center, tap **Settings**, and then tap **User Names**.
2. Tap **Add User Account**.
3. Enter the following information:
   - **User Name** - The name of the user to save for use with a remote connection. You can enter the user name in any of the following formats: user_name, domain\user_name, or user_name@domain.com.
   - **Password** - The password for the user you specified. Every user account that you want to save to use for remote connections needs to have a password associated with it.
4. Tap **Save**, and then tap **Settings**.
5. Tap **Done** to save the  new configuration.

To delete a user account:

1. In the Connection Center, tap **Settings > User Names**.
2. Swipe the row from right to left to select the user.
3. Tap **Delete**.

## Remote resources
Remote resources are RemoteApp programs, session-based desktops, and virtual desktops published using RemoteApp and Desktop Connections.

- The URL displays the link to the RD Web Access server enabling access to RemoteApp and Desktop Connections.
- The configured RemoteApp and Desktop Connections are listed.

To add remote resources:

1. On the Connection Center screen, tap **+**, and then tap **Add Remote Resources**. 
2. Enter information for the remote resource:
   - **Feed URL** - The URL of the RD Web Access server. You can also enter your corporate email account in this field – this tells the client to search for the RD Web Access Server associated with your email address.
   - **User name** - The user name to use for the RD Web Access server you are connecting to.
   - **Password** - The password to use for the RD Web Access server you are connecting to.
3. Tap **Save**.

The remote resources will be displayed in the Connection Center.


To delete remote resources:

1. In the Connection Center, press and hold any of the applications or desktops in the remote resources or the name of the application feed.
2. Tap **Settings** on the URL name.
2. Tap **Delete**.
3. Confirm the deletion.


## Navigating the Remote Desktop Session
When you start a remote desktop connection, there are tools available that you can use to navigate the session.

### Start a Remote Desktop Connection

1. Tap the remote desktop connection to start the remote desktop session. 
2. If you are asked to verify the certificate for the remote desktop, tap **Accept**. You can choose to always accept by sliding the  **Don’t ask me again for connections to this computer** toggle to **ON**. 

### Connection Bar

The connection bar gives you access to additional navigation controls. 

- **Pan Control**: The pan control enables the screen to be enlarged and moved around. Note that pan control is only available using direct touch.
   - Enable / Disable the pan control: Tap the pan icon in the connection bar to display the pan control and zoom the screen. Tap the pan icon in the connection bar again to hide the control and return the screen to its original resolution.
   - Use the pan control: Tap and hold the pan control and then drag in the direction you want to move the screen.
   - Move the pan control: Double tap and hold the pan control to move the control on the screen.
- **Connection name**: The current connection name is displayed. Tap the connection name to display the session selection bar.
- **Keyboard**: Tap the keyboard icon to display or hide the keyboard. The pan control is displayed automatically when the keyboard is displayed.
- **Move the connection bar**: Tap and hold the connection bar, and then drag and drop to a new location at the top of the screen.

### Session selection
You can have multiple connections open to different PCs at the same time. Tap the connection bar to display the session selection bar on the left-hand side of the screen. The session selection bar enables you to view your open connections and switch between them. 

- Switch between apps in an open remote resource session.

    When you are connected to remote resources, you can switch between open applications within that session by tapping the expander menu and choosing from the list of available items.
- Start a new session

  You can start new applications or desktop sessions from within your current connection: tap **Start New**, and then choose from the list of available items.

- Disconnection a session

  To disconnect a session tap X in the left-hand side of the session tile.

### Command bar

The command bar replaced the Utility bar starting in version 8.0.1. You can switch between the mouse modes and return to the connection center from the command bar.

### Direct touch gestures and mouse modes

The client uses standard touch gestures. You can also use touch gestures to replicate mouse actions on the remote desktop. The mouse modes available are defined in the table below.

> [!NOTE]
> Interacting with Windows 8 or newer the native touch gestures are supported in Direct Touch mode. For more information on Windows 8 gestures see [Touch: Swipe, tap, and beyond](http://windows.microsoft.com/en-US/windows-8/touch-swipe-tap-beyond).

| Mouse mode    | Mouse operation      | Gesture                                                    |
|---------------|----------------------|------------------------------------------------------------|
| Direct touch  | Left click           | 1 finger tap                                               |
| Direct touch  | Right click          | 1 finger tap and hold                                      |
| Mouse pointer | Left click           | 1 finger tap                                               |
| Mouse pointer | Left click and drag  | 1 finger double tap and hold, then drag                    |
| Mouse pointer | Right click          | 2 finger tap                                               |
| Mouse pointer | Right click and drag | 2 finger double tap and hold, then drag                    |
| Mouse pointer | Mouse wheel          | 2 finger tap and hold, then drag up or down                |
| Mouse pointer | Zoom                 | Pinch 2 fingers to zoom in or spread 2 fingers to zoom out |

## On-screen keyboards
On the iPad and iPhone you can use the button on the right edge of the bar above the keyboard to switch between the standard and additional keyboard.

## Bluetooth keyboard
If Bluetooth is enabled, a Bluetooth keyboard should be automatically detected.

Due to limitations on the OS, special keys such as Ctrl, Option, and Function will not work as expected. The following keys currently work:

- Alphanumeric keys
- Cursor keys
- Tab: Tab works, but Shift+Tab does not work
- Home / Pos1: Alt+Left = Home
- End: Alt+Right = End
- Page Up: Alt+Up = Page Up
- Page Down: Alt+Down = Page Down
- Select All: Command+A = Ctrl+A (Select all in most programs)
- Cut: Command+X = Ctrl+X (Cut in most programs)
- Copy: Command+C = Ctrl+C (Copy in most programs)
- Paste: Command+V = Ctrl+V (Paste in most programs)
- Symbols: Alt+Alphanumeric keys will produce different symbols depending on the language configured



> [!TIP]
> Questions and comments are always welcome. However, please do NOT post a request for troubleshooting help by using the comment feature at the end of this article. Instead, go to the [Remote Desktop client forum](http://social.technet.microsoft.com/forums/windowsserver/en-us/home?forum=winrdc) and start a new thread. Have a feature suggestion? Tell us in the [client user voice forum](https://remotedesktop.uservoice.com/forums/272085-remote-desktop-for-android).