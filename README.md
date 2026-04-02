# Settings URL schemes for macOS 26 Tahoe

<br>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs that have been copied from outside sources_</sup>

<br>
<br>

_Apple Account_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings
~~~
_Apple Account › Personal Information_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPersonalInfoUI
~~~
_Apple Account › Sign-In & Security_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPasswordSecurityUI
~~~
_Apple Account › Sign-In & Security › Legacy Contact_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/accountDetails?root=APPLE_ACCOUNT&path=accountBeneficiary
~~~
_Apple Account › Payment & Shipping_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPaymentUI
~~~
_Apple Account › iCloud_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?iCloud
~~~
_Apple Account › iCloud › Manage › Manage Storage_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?path=STORAGE_AND_BACKUP
~~~
_Apple Account › iCloud › Manage › Manage Storage › Backups_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP
~~~
_Apple Account › iCloud › See All › Saved to iCloud_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/SHOW_ALL_APPS
~~~
_Apple Account › iCloud › See All › Saved to iCloud › Find My Mac_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.DeviceLocator
~~~
_Apple Account › iCloud › Photos_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.CloudPhotos
~~~
_Apple Account › iCloud › Drive_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Ubiquity
~~~
_Apple Account › iCloud › Passwords_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.KeychainSync
~~~
_Apple Account › iCloud › Notes_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Notes
~~~
_Apple Account › iCloud › Messages_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Messages
~~~
_Apple Account › iCloud › Mail_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Mail
~~~
_Apple Account › iCloud › iCloud+ Features › Private Relay_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/accountDetails?path=InternetPrivacy
~~~
_Apple Account › iCloud › iCloud+ Features › Hide My Email_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE
~~~
_Apple Account › iCloud › Advanced Data Protection_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME
~~~
_Apple Account › Media & Purchases_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?com.apple.AppleMediaServicesUI.SpyglassPurchases
~~~
_Apple Account › Sign in with Apple_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?signInWithApple
~~~

<br>

_Family_
~~~csv
x-apple.systempreferences:com.apple.Family-Settings.extension
~~~
_Family › Subscriptions_
~~~csv
x-apple.systempreferences:com.apple.Family-Settings.extension?familyPath=/subscriptions
~~~

<br>

_Wi-Fi_
~~~csv
x-apple.systempreferences:com.apple.wifi-settings-extension
~~~
_Wi-Fi › [current network] › Details_
~~~csv
x-apple.systempreferences:com.apple.wifi-settings-extension?NetworkDetails
~~~
_Wi-Fi › Advanced_
~~~csv
x-apple.systempreferences:com.apple.wifi-settings-extension?Advanced
~~~

<br>

_Bluetooth_
~~~csv
x-apple.systempreferences:com.apple.BluetoothSettings
~~~

<br>

_Network_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension
~~~
_Network › [current network] › TCP/IP_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?TCP/IP
~~~
_Network › [current network] › DNS_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?DNS
~~~
_Network › [current network] › WINS_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?WINS
~~~
_Network › [current network] › 802.1X_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?802.1X
~~~
_Network › [current network] › Proxies <sub>some delay</sub>_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?Proxies
~~~
_Network › [current network] › Hardware <sub>some delay</sub>_
~~~csv
x-apple.systempreferences:com.apple.Network-Settings.extension?Hardware
~~~

<br>

_Battery_
~~~csv
x-apple.systempreferences:com.apple.Battery-Settings.extension
~~~
_Battery › Battery Health_
~~~csv
x-apple.systempreferences:com.apple.Battery-Settings.extension?batteryhealth
~~~
_Battery › Options_
~~~csv
x-apple.systempreferences:com.apple.Battery-Settings.extension?options
~~~

<br>

_General_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.GeneralSettings
~~~

<br>

_General › About_
~~~csv
x-apple.systempreferences:com.apple.SystemProfiler.AboutExtension
~~~

<br>

_General › Software Update_
~~~csv
x-apple.systempreferences:com.apple.Software-Update-Settings.extension
~~~
_General › Software Update › Automatic Updates_
~~~csv
x-apple.systempreferences:com.apple.Software-Update-Settings.extension?action=showAdvancedOptions
~~~
_General › Software Update › Beta Updates <sub>some delay</sub>_
~~~csv
x-apple.systempreferences:com.apple.Software-Update-Settings.extension?action=showBetaUpdates
~~~

<br>

_General › Storage_
~~~csv
x-apple.systempreferences:com.apple.settings.Storage
~~~

<br>

_General › AppleCare & Warranty_
~~~csv
x-apple.systempreferences:com.apple.Coverage-Settings.extension
~~~

<br>

_General › AirDrop & Handoff_
~~~csv
x-apple.systempreferences:com.apple.AirDrop-Handoff-Settings.extension
~~~

<br>

_General › AutoFill & Passwords_
~~~csv
x-apple.systempreferences:com.apple.Passwords-Settings.extension
~~~

<br>

_General › Date & Time_
~~~csv
x-apple.systempreferences:com.apple.Date-Time-Settings.extension
~~~

<br>

_General › Language & Region_
~~~csv
x-apple.systempreferences:com.apple.Localization-Settings.extension
~~~
_General › Language & Region › Translation Languages_
~~~csv
x-apple.systempreferences:com.apple.Localization-Settings.extension?translation
~~~
_General › Language & Region › Translation Languages › Translation & Privacy_
~~~csv
x-apple.systempreferences:com.apple.Localization-Settings.extension?translation-privacy
~~~

<br>

_General › Login Items & Extensions_
~~~csv
x-apple.systempreferences:com.apple.LoginItems-Settings.extension
~~~
_General › Login Items & Extensions › Open at Login [section]_
~~~csv
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?UserItems
~~~
_General › Login Items & Extensions › App Background Activity [section]_
~~~csv
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?BackgroundItems
~~~
_General › Login Items & Extensions › Extensions [section]_
~~~csv
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?ExtensionItems
~~~
_General › Login Items & Extensions › Extensions › By App › Books_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Books.app
~~~
_General › Login Items & Extensions › Extensions › By App › Freeform_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Freeform.app
~~~
_General › Login Items & Extensions › Extensions › By App › Journal_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Journal.app
~~~
_General › Login Items & Extensions › Extensions › By App › Messages_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Messages.app
~~~
_General › Login Items & Extensions › Extensions › By App › Notes_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Notes.app
~~~
_General › Login Items & Extensions › Extensions › By App › Reminders_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Reminders.app
~~~
_General › Login Items & Extensions › Extensions › By App › Shortcuts_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Shortcuts.app
~~~
_General › Login Items & Extensions › Extensions › By App › [file system path of application, e.g. /Applications/Name of App.app]_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=replace_with_path_of_app
~~~
_General › Login Items & Extensions › Extensions › By Category › Actions_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.ui-services
~~~
_General › Login Items & Extensions › Extensions › By Category › File Providers_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.fileprovider-nonui
~~~
_General › Login Items & Extensions › Extensions › By Category › File System Extensions_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.fskit.fsmodule
~~~
_General › Login Items & Extensions › Extensions › By Category › Finder_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.finder-quick-actions
~~~
_General › Login Items & Extensions › Extensions › By Category › Network_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.networkextension.app-proxy
~~~
_General › Login Items & Extensions › Extensions › By Category › Photos Editing_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.photo-editing
~~~
_General › Login Items & Extensions › Extensions › By Category › Sharing_
~~~csv
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.share-services
~~~

<br>

_General › Sharing_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension
~~~
_General › Sharing › Content & Media › Screen Sharing_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_ScreenSharing
~~~
_General › Sharing › Accessories & Internet › Printer Sharing_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_PrinterSharing
~~~
_General › Sharing › Accessories & Internet › Internet Sharing_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Internet
~~~
_General › Sharing › Advanced › Remote Management_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_ARDService
~~~
_General › Sharing › Advanced › Remote Login_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_RemoteLogin
~~~
_General › Sharing › Advanced › Remote Application Scripting_
~~~csv
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_RemoteAppleEvent
~~~

<br>

_General › Startup Disk_
~~~csv
x-apple.systempreferences:com.apple.Startup-Disk-Settings.extension
~~~

<br>

_General › Time Machine_
~~~csv
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension
~~~
_General › Time Machine › Add Backup Disk_
~~~csv
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension?chooseDestination
~~~
_General › Time Machine › Options_
~~~csv
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension?options
~~~

<br>

_General › Device Management_
~~~csv
x-apple.systempreferences:com.apple.Profiles-Settings.extension
~~~

<br>

_General › Transfer or Reset_
~~~csv
x-apple.systempreferences:com.apple.Transfer-Reset-Settings.extension
~~~

<br>

_Accessibility_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension
~~~

<br>

_Accessibility › VoiceOver_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VoiceOver
~~~

<br>

_Accessibility › Zoom_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Zoom
~~~
_Accessibility › Zoom › Choose Display_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_ZOOM_CHOOSE_DISPLAY
~~~
_Accessibility › Zoom › Advanced_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_ZOOM_TOGGLE_FS_AND_PIP
~~~

<br>

_Accessibility › Hover Text_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?HoverText
~~~
_Accessibility › Hover Text › Hover Text_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?hoverTextSettings
~~~
_Accessibility › Hover Text › Hover Typing_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?hoverTypingSettings
~~~

<br>

_Accessibility › Display_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Display
~~~
_Accessibility › Display › Text Size_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_FONT_SIZE
~~~

<br>

_Accessibility › Motion_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Motion
~~~

<br>

_Accessibility › Read & Speak_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?SpokenContent
~~~
_Accessibility › Read & Speak › Speak selection_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_SELECTION_SHOW_CONTROLLER
~~~
_Accessibility › Read & Speak › Speak item under the pointer_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_POINTER_ELEMENT_MODE
~~~
_Accessibility › Read & Speak › Speak announcements_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPEECH_TEST
~~~
_Accessibility › Read & Speak › Speak typing feedback_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_TYPING_ECHO_CHARS
~~~
_Accessibility › Read & Speak › Pronunciations_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_PRONUNCIATIONS_EDIT
~~~

<br>

_Accessibility › Audio Descriptions_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Descriptions
~~~

<br>

_Accessibility › Hearing Devices_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Hearing
~~~

<br>

_Accessibility › Audio_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Audio
~~~

<br>

_Accessibility › RTT_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?RTT
~~~

<br>

_Accessibility › Captions_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Captions
~~~

<br>

_Accessibility › Live Captions_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?LiveCaptions
~~~

<br>

_Accessibility › Name Recognition_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?NameRecognition
~~~

<br>

_Accessibility › Voice Control_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VoiceControl
~~~
_Accessibility › Voice Control › Commands_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_VOICE_CONTROL_COMMANDS
~~~
_Accessibility › Voice Control › Vocabulary_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_VOICE_CONTROL_VOCABULARY
~~~

<br>

_Accessibility › Keyboard_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Keyboard
~~~
_Accessibility › Keyboard › Full Keyboard Access_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?fullKeyboardAccessOptions
~~~
_Accessibility › Keyboard › Sticky Keys_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_STICKY_KEYS_BEEP
~~~
_Accessibility › Keyboard › Slow Keys_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?slowKeysOptions
~~~
_Accessibility › Keyboard › Accessibility Keyboard_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_KB_APPEARANCE_TYPE
~~~

<br>

_Accessibility › Pointer Control_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?PointerControl
~~~
_Accessibility › Pointer Control › Trackpad Options_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_TRACKPAD_OPTIONS
~~~
_Accessibility › Pointer Control › Mouse Options_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_MOUSE_OPTIONS
~~~
_Accessibility › Pointer Control › Mouse Keys_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_MOUSE_KEYS_SHORTCUT
~~~
_Accessibility › Pointer Control › Alternative pointer actions_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_CONFIGURE_CAMERA
~~~
_Accessibility › Pointer Control › Head pointer_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_HEAD_MOUSE_BUTTON
~~~

<br>

_Accessibility › Switch Control_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?SwitchControl
~~~
_Accessibility › Switch Control › Switch Timing_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SWITCH_TIMING
~~~
_Accessibility › Switch Control › Navigation Timing_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_NAVIGATION_TIMING
~~~

<br>

_Accessibility › Live Speech_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?LiveSpeech
~~~

<br>

_Accessibility › Personal Voice_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?PersonalVoice
~~~

<br>

_Accessibility › Vocal Shortcuts_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VocalShortcuts
~~~

<br>

_Accessibility › Siri_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Siri
~~~

<br>

_Accessibility › Shortcut_
~~~csv
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Shortcut
~~~

<br>

_Appearance_
~~~csv
x-apple.systempreferences:com.apple.Appearance-Settings.extension
~~~

<br>

_Menu Bar_
~~~csv
x-apple.systempreferences:com.apple.ControlCenter-Settings.extension
~~~
_Menu Bar › Clock Options_
~~~csv
x-apple.systempreferences:com.apple.ControlCenter-Settings.extension?Clock
~~~

<br>

_Apple Intelligence & Siri_
~~~csv
x-apple.systempreferences:com.apple.Siri-Settings.extension
~~~
_Apple Intelligence & Siri › Siri Suggestions & Privacy_
~~~csv
x-apple.systempreferences:com.apple.Siri-Settings.extension?siriSuggestions
~~~
_Apple Intelligence & Siri › Siri Suggestions & Privacy › [bundle ID of app]_
~~~csv
x-apple.systempreferences:com.apple.Siri-Settings.extension?siriSuggestions&bundleId=replace_with_app_bundle_id
~~~

<br>

_Desktop & Dock_
~~~csv
x-apple.systempreferences:com.apple.Desktop-Settings.extension
~~~
_Desktop & Dock › Hot Corners_
~~~csv
x-apple.systempreferences:com.apple.Desktop-Settings.extension?HotCorners
~~~
_Desktop & Dock › Shortcuts_
~~~csv
x-apple.systempreferences:com.apple.Desktop-Settings.extension?Shortcuts
~~~

<br>

_Displays_
~~~csv
x-apple.systempreferences:com.apple.Displays-Settings.extension
~~~
_Displays › Advanced_
~~~csv
x-apple.systempreferences:com.apple.Displays-Settings.extension?advancedSection
~~~
_Displays › Night Shift_
~~~csv
x-apple.systempreferences:com.apple.Displays-Settings.extension?nightShiftSection
~~~

<br>

_Spotlight_
~~~csv
x-apple.systempreferences:com.apple.Spotlight-Settings.extension
~~~
_Spotlight › Search Privacy_
~~~csv
x-apple.systempreferences:com.apple.Spotlight-Settings.extension?privacy
~~~

<br>

_Wallpaper_
~~~csv
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension
~~~
_Wallpaper › Screen Saver_
~~~csv
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension?ScreenSaver
~~~
_Wallpaper › Clock Appearance_
~~~csv
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension?ClockAppearance
~~~

<br>

_Notifications_
~~~csv
x-apple.systempreferences:com.apple.Notifications-Settings.extension
~~~
_Notifications › Allow Notifications from iPhone_
~~~csv
x-apple.systempreferences:com.apple.Notifications-Settings.extension?RemoteNotifications
~~~
_Notifications › [bundle ID of app]_
~~~csv
x-apple.systempreferences:com.apple.Notifications-Settings.extension?id=replace_with_app_bundle_id
~~~

<br>

_Sound_
~~~csv
x-apple.systempreferences:com.apple.Sound-Settings.extension
~~~
_Sound › Output [tab]_
~~~csv
x-apple.systempreferences:com.apple.Sound-Settings.extension?output
~~~
_Sound › Input [tab]_
~~~csv
x-apple.systempreferences:com.apple.Sound-Settings.extension?input
~~~

<br>

_Focus_
~~~csv
x-apple.systempreferences:com.apple.Focus-Settings.extension
~~~

<br>

_Screen Time_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension
~~~
_Screen Time › App & Website Activity <sub>when App & Website Activity is enabled</sub>_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=app-usage
~~~
_Screen Time › Notifications <sub>when App & Website Activity is enabled</sub>_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=notifications
~~~
_Screen Time › Pickups <sub>when App & Website Activity is enabled</sub>_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=pickups
~~~
_Screen Time › Downtime <sub>when App & Website Activity is enabled</sub>_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=downtime
~~~
_Screen Time › App Limits <sub>when App & Website Activity is enabled</sub>_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=app-limits
~~~
_Screen Time › Always Allowed_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=always-allowed
~~~
_Screen Time › Screen Distance_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=screen-distance
~~~
_Screen Time › Communication Limits_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=communication-limits
~~~
_Screen Time › Communications Safety_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=communication-safety
~~~
_Screen Time › Content & Privacy_
~~~csv
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=content-and-privacy
~~~

<br>

_Lock Screen_
~~~csv
x-apple.systempreferences:com.apple.Lock-Screen-Settings.extension
~~~

<br>

_Privacy & Security_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension
~~~
_Privacy & Security › Location Services_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_LocationServices
~~~
_Privacy & Security › Location Services › System Services_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_SystemServices
~~~
_Privacy & Security › Calendars_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Calendars
~~~
_Privacy & Security › Contacts_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Contacts
~~~
_Privacy & Security › Files & Folders_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_FilesAndFolders
~~~
_Privacy & Security › Full Disk Access_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AllFiles
~~~
_Privacy & Security › Home_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_HomeKit
~~~
_Privacy & Security › Media & Apple Music_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Media
~~~
_Privacy & Security › Passkeys Access for Web Browsers_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_PasskeyAccess
~~~
_Privacy & Security › Photos_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Photos
~~~
_Privacy & Security › Reminders_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Reminders
~~~
_Privacy & Security › Accessibility_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Accessibility
~~~
_Privacy & Security › App Management_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AppBundles
~~~
_Privacy & Security › Automation_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Automation
~~~
_Privacy & Security › Bluetooth_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Bluetooth
~~~
_Privacy & Security › Camera_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Camera
~~~
_Privacy & Security › Developer Tools_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_DevTools
~~~
_Privacy & Security › Focus_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Focus
~~~
_Privacy & Security › Input Monitoring_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_ListenEvent
~~~
_Privacy & Security › Microphone_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Microphone
~~~
_Privacy & Security › Motion & Fitness_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Motion
~~~
_Privacy & Security › Remote Desktop_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_RemoteDesktop
~~~
_Privacy & Security › Screen & System Audio Recording_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AudioCapture
~~~
_Privacy & Security › Speech Recognition_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_SpeechRecognition
~~~
_Privacy & Security › Sensitive Content Warning_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_NudityDetection
~~~
_Privacy & Security › Blocked Contacts_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Blocklist
~~~
_Privacy & Security › Analytics & Improvements_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Analytics
~~~
_Privacy & Security › Apple Advertising_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Advertising
~~~
_Privacy & Security › Apple Intelligence Report_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AppleIntelligenceReport
~~~
_Privacy & Security › Gatekeeper_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Security
~~~
_Privacy & Security › FileVault_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?FileVault
~~~
_Privacy & Security › Accessories_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Accessories
~~~
_Privacy & Security › Lockdown Mode_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?LockdownMode
~~~
_Privacy & Security › Background Security Improvements_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?SecurityImprovements
~~~
_Privacy & Security › Advanced_
~~~csv
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Advanced
~~~

<br>

_Touch ID & Password_
~~~csv
x-apple.systempreferences:com.apple.Touch-ID-Settings.extension
~~~

<br>

_Users & Groups_
~~~csv
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension
~~~
_Users & Groups › [current user]_
~~~csv
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo
~~~
_Users & Groups › [current user] › Password › Change_
~~~csv
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?changepassword
~~~
_Users & Groups › [full name of user or name of user's home folder]_
~~~csv
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo*user:replace_with_full_or_short_name_of_user
~~~
_Users & Groups › Guest User_
~~~csv
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo*user:guest
~~~

<br>

_Internet Accounts_
~~~csv
x-apple.systempreferences:com.apple.Internet-Accounts-Settings.extension
~~~
_Internet Accounts › Add Account_
~~~csv
x-apple.systempreferences:com.apple.Internet-Accounts-Settings.extension?ADD_ACCOUNT
~~~

<br>

_Game Center_
~~~csv
x-apple.systempreferences:com.apple.Game-Center-Settings.extension
~~~
_Game Center › Customize Profile_
~~~csv
x-apple.systempreferences:com.apple.Game-Center-Settings?EDIT_PROFILE
~~~
_Game Center › All Friends_
~~~csv
x-apple.systempreferences:com.apple.Game-Center-Settings?ALL_FRIENDS
~~~
_Game Center › Friend Requests_
~~~csv
x-apple.systempreferences:com.apple.Game-Center-Settings?FRIEND_REQUESTS
~~~
_Game Center › Invite Friends_
~~~csv
x-apple.systempreferences:com.apple.Game-Center-Settings?INVITE_FRIENDS
~~~

<br>

_iCloud <sub>for more URLs, see Apple Account › iCloud</sub>_
~~~csv
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings:icloud
~~~

<br>

_Wallet & Apple Pay_
~~~csv
x-apple.systempreferences:com.apple.WalletSettingsExtension
~~~
_Wallet & Apple Pay › Add Card_
~~~csv
x-apple.systempreferences:com.apple.WalletSettingsExtension?fpanImportPrivacy
~~~
_Wallet & Apple Pay › AutoFill Cards_
~~~csv
x-apple.systempreferences:com.apple.WalletSettingsExtension?autoFillPane
~~~

<br>

_AirPods [the name of your AirPods] <sub>append ‘?’ followed by the MAC address of the AirPods in case you have more than one set connected_
~~~csv
x-apple.systempreferences:com.apple.HeadphoneSettings
~~~

<br>

_Keyboard_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension
~~~
_Keyboard › Keyboard Shortcuts › Spotlight_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?Spotlight
~~~
_Keyboard › Keyboard Shortcuts › Function keys_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?FunctionKeys
~~~
_Keyboard › Keyboard Shortcuts › Modifier keys_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?ModifierKeys
~~~
_Keyboard › Text Input › Edit_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?InputSources
~~~
_Keyboard › Text Input › Text Replacements_
~~~csv
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?TextReplacements
~~~

<br>

_Trackpad_
~~~csv
x-apple.systempreferences:com.apple.Trackpad-Settings.extension
~~~
_Trackpad › Point & Click [tab]_
~~~csv
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?PointAndClick
~~~
_Trackpad › Scroll & Zoom [tab]_
~~~csv
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?ScrollAndZoom
~~~
_Trackpad › More Gestures [tab]_
~~~csv
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?MoreGestures
~~~

<br>

_Game Controllers_
~~~csv
x-apple.systempreferences:com.apple.Game-Controller-Settings.extension
~~~

<br>

_Printers & Scanners_
~~~csv
x-apple.systempreferences:com.apple.preference.printfax
~~~
