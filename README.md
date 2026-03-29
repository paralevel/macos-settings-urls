# Settings URL schemes for macOS 26 Tahoe

<br>

<sup>_Credit: https://www.w3.org/People/Berners-Lee/ • https://www.apple.com_</sup>

<sup>_Disclaimer: This collection only includes URLs I have been able to find or reverse engineer myself, using data extracted from local system files, and not URLs copied from other online sources_</sup>

<br>
<br>

_Apple Account_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings
~~~
_Apple Account > Personal Information_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPersonalInfoUI
~~~
_Apple Account > Sign-In & Security_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPasswordSecurityUI
~~~
_Apple Account > Sign-In & Security > Legacy Contact_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/accountDetails?root=APPLE_ACCOUNT&path=accountBeneficiary
~~~
_Apple Account > Payment & Shipping_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?loadPaymentUI
~~~
_Apple Account > iCloud_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?iCloud
~~~
_Apple Account > iCloud > Manage > Manage Storage_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?path=STORAGE_AND_BACKUP
~~~
_Apple Account > iCloud > Manage > Manage Storage > Backups_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/BACKUP
~~~
_Apple Account > iCloud > See All > Saved to iCloud_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/SHOW_ALL_APPS
~~~
_Apple Account > iCloud > See All > Saved to iCloud > Find My Mac_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.DeviceLocator
~~~
_Apple Account > iCloud > Photos_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.CloudPhotos
~~~
_Apple Account > iCloud > Drive_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Ubiquity
~~~
_Apple Account > iCloud > Passwords_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.KeychainSync
~~~
_Apple Account > iCloud > Notes_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Notes
~~~
_Apple Account > iCloud > Messages_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Messages
~~~
_Apple Account > iCloud > Mail_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE&dataclassId=com.apple.Dataclass.Mail
~~~
_Apple Account > iCloud > iCloud+ Features > Private Relay_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/accountDetails?path=InternetPrivacy
~~~
_Apple Account > iCloud > iCloud+ Features > Hide My Email_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/PRIVATE_EMAIL_MANAGE
~~~
_Apple Account > iCloud > Advanced Data Protection_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?email/prefs/storage?root=APPLE_ACCOUNT&path=ICLOUD_SERVICE/ICLOUD_ADP_SPECIFIER_NAME
~~~
_Apple Account > Media & Purchases_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?com.apple.AppleMediaServicesUI.SpyglassPurchases
~~~
_Apple Account > Sign in with Apple_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings?signInWithApple
~~~
\
\
_Family_
~~~yaml
x-apple.systempreferences:com.apple.Family-Settings.extension
~~~
_Family > Subscriptions_
~~~yaml
x-apple.systempreferences:com.apple.Family-Settings.extension?familyPath=/subscriptions
~~~
\
\
_Wi-Fi_
~~~yaml
x-apple.systempreferences:com.apple.wifi-settings-extension
~~~
_Wi-Fi > [current network] > Details_
~~~yaml
x-apple.systempreferences:com.apple.wifi-settings-extension?NetworkDetails
~~~
_Wi-Fi > Advanced_
~~~yaml
x-apple.systempreferences:com.apple.wifi-settings-extension?Advanced
~~~
\
\
_Bluetooth_
~~~yaml
x-apple.systempreferences:com.apple.BluetoothSettings
~~~
\
\
_Network_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension
~~~
_Network > [current network] > TCP/IP_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?TCP/IP
~~~
_Network > [current network] > DNS_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?DNS
~~~
_Network > [current network] > WINS_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?WINS
~~~
_Network > [current network] > 802.1X_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?802.1X
~~~
_Network > [current network] > Proxies <sub>some delay</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?Proxies
~~~
_Network > [current network] > Hardware <sub>some delay</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Network-Settings.extension?Hardware
~~~
\
\
_Battery_
~~~yaml
x-apple.systempreferences:com.apple.Battery-Settings.extension
~~~
_Battery > Battery Health_
~~~yaml
x-apple.systempreferences:com.apple.Battery-Settings.extension?batteryhealth
~~~
_Battery > Options_
~~~yaml
x-apple.systempreferences:com.apple.Battery-Settings.extension?options
~~~
\
\
_General_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.GeneralSettings
~~~
\
\
_General > About_
~~~yaml
x-apple.systempreferences:com.apple.SystemProfiler.AboutExtension
~~~
\
\
_General > Software Update_
~~~yaml
x-apple.systempreferences:com.apple.Software-Update-Settings.extension
~~~
_General > Software Update > Automatic Updates_
~~~yaml
x-apple.systempreferences:com.apple.Software-Update-Settings.extension?action=showAdvancedOptions
~~~
_General > Software Update > Beta Updates <sub>some delay</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Software-Update-Settings.extension?action=showBetaUpdates
~~~
\
\
_General > Storage_
~~~yaml
x-apple.systempreferences:com.apple.settings.Storage
~~~
\
\
_General > AppleCare & Warranty_
~~~yaml
x-apple.systempreferences:com.apple.Coverage-Settings.extension
~~~
\
\
_General > AirDrop & Handoff_
~~~yaml
x-apple.systempreferences:com.apple.AirDrop-Handoff-Settings.extension
~~~
\
\
_General > AutoFill & Passwords_
~~~yaml
x-apple.systempreferences:com.apple.Passwords-Settings.extension
~~~
\
\
_General > Date & Time_
~~~yaml
x-apple.systempreferences:com.apple.Date-Time-Settings.extension
~~~
\
\
_General > Language & Region_
~~~yaml
x-apple.systempreferences:com.apple.Localization-Settings.extension
~~~
_General > Language & Region > Translation Languages_
~~~yaml
x-apple.systempreferences:com.apple.Localization-Settings.extension?translation
~~~
_General > Language & Region > Translation Languages > Translation & Privacy_
~~~yaml
x-apple.systempreferences:com.apple.Localization-Settings.extension?translation-privacy
~~~
\
\
_General > Login Items & Extensions_
~~~yaml
x-apple.systempreferences:com.apple.LoginItems-Settings.extension
~~~
_General > Login Items & Extensions > Open at Login (section)_
~~~yaml
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?UserItems
~~~
_General > Login Items & Extensions > App Background Activity (section)_
~~~yaml
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?BackgroundItems
~~~
_General > Login Items & Extensions > Extensions (section)_
~~~yaml
x-apple.systempreferences:com.apple.LoginItems-Settings.extension?ExtensionItems
~~~
_General > Login Items & Extensions > Extensions > By App > Books_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Books.app
~~~
_General > Login Items & Extensions > Extensions > By App > Freeform_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Freeform.app
~~~
_General > Login Items & Extensions > Extensions > By App > Journal_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Journal.app
~~~
_General > Login Items & Extensions > Extensions > By App > Messages_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Messages.app
~~~
_General > Login Items & Extensions > Extensions > By App > Notes_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Notes.app
~~~
_General > Login Items & Extensions > Extensions > By App > Reminders_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Reminders.app
~~~
_General > Login Items & Extensions > Extensions > By App > Shortcuts_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=/System/Applications/Shortcuts.app
~~~
_General > Login Items & Extensions > Extensions > By App > [file system path of application, e.g. /Applications/Name of App.app]_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?applicationPath=replace_with_path_of_app
~~~
_General > Login Items & Extensions > Extensions > By Category > Actions_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.ui-services
~~~
_General > Login Items & Extensions > Extensions > By Category > File Providers_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.fileprovider-nonui
~~~
_General > Login Items & Extensions > Extensions > By Category > File System Extensions_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.fskit.fsmodule
~~~
_General > Login Items & Extensions > Extensions > By Category > Finder_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.finder-quick-actions
~~~
_General > Login Items & Extensions > Extensions > By Category > Network_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.networkextension.app-proxy
~~~
_General > Login Items & Extensions > Extensions > By Category > Photos Editing_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.photo-editing
~~~
_General > Login Items & Extensions > Extensions > By Category > Sharing_
~~~yaml
x-apple.systempreferences:com.apple.ExtensionsPreferences?extensionPointIdentifier=com.apple.share-services
~~~
\
\
_General > Sharing_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension
~~~
_General > Sharing > Content & Media > Screen Sharing_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_ScreenSharing
~~~
_General > Sharing > Accessories & Internet > Printer Sharing_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_PrinterSharing
~~~
_General > Sharing > Accessories & Internet > Internet Sharing_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Internet
~~~
_General > Sharing > Advanced > Remote Management_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_ARDService
~~~
_General > Sharing > Advanced > Remote Login_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_RemoteLogin
~~~
_General > Sharing > Advanced > Remote Application Scripting_
~~~yaml
x-apple.systempreferences:com.apple.Sharing-Settings.extension?Services_RemoteAppleEvent
~~~
\
\
_General > Startup Disk_
~~~yaml
x-apple.systempreferences:com.apple.Startup-Disk-Settings.extension
~~~
\
\
_General > Time Machine_
~~~yaml
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension
~~~
_General > Time Machine > Add Backup Disk_
~~~yaml
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension?chooseDestination
~~~
_General > Time Machine > Options_
~~~yaml
x-apple.systempreferences:com.apple.Time-Machine-Settings.extension?options
~~~
\
\
_General > Device Management_
~~~yaml
x-apple.systempreferences:com.apple.Profiles-Settings.extension
~~~
\
\
_General > Transfer or Reset_
~~~yaml
x-apple.systempreferences:com.apple.Transfer-Reset-Settings.extension
~~~
\
\
_Accessibility_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension
~~~
\
\
_Accessibility > VoiceOver_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VoiceOver
~~~
\
\
_Accessibility > Zoom_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Zoom
~~~
_Accessibility > Zoom > Choose Display_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_ZOOM_CHOOSE_DISPLAY
~~~
_Accessibility > Zoom > Advanced_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_ZOOM_TOGGLE_FS_AND_PIP
~~~
\
\
_Accessibility > Hover Text_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?HoverText
~~~
_Accessibility > Hover Text > Hover Text_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?hoverTextSettings
~~~
_Accessibility > Hover Text > Hover Typing_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?hoverTypingSettings
~~~
\
\
_Accessibility > Display_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Display
~~~
_Accessibility > Display > Text Size_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_FONT_SIZE
~~~
\
\
_Accessibility > Motion_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Motion
~~~
\
\
_Accessibility > Read & Speak_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?SpokenContent
~~~
_Accessibility > Read & Speak > Speak selection_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_SELECTION_SHOW_CONTROLLER
~~~
_Accessibility > Read & Speak > Speak item under the pointer_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_POINTER_ELEMENT_MODE
~~~
_Accessibility > Read & Speak > Speak announcements_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPEECH_TEST
~~~
_Accessibility > Read & Speak > Speak typing feedback_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_TYPING_ECHO_CHARS
~~~
_Accessibility > Read & Speak > Pronunciations_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SPOKEN_PRONUNCIATIONS_EDIT
~~~
\
\
_Accessibility > Audio Descriptions_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Descriptions
~~~
\
\
_Accessibility > Hearing Devices_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Hearing
~~~
\
\
_Accessibility > Audio_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Audio
~~~
\
\
_Accessibility > RTT_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?RTT
~~~
\
\
_Accessibility > Captions_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Captions
~~~
\
\
_Accessibility > Live Captions_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?LiveCaptions
~~~
\
\
_Accessibility > Name Recognition_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?NameRecognition
~~~
\
\
_Accessibility > Voice Control_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VoiceControl
~~~
_Accessibility > Voice Control > Commands_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_VOICE_CONTROL_COMMANDS
~~~
_Accessibility > Voice Control > Vocabulary_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_VOICE_CONTROL_VOCABULARY
~~~
\
\
_Accessibility > Keyboard_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Keyboard
~~~
_Accessibility > Keyboard > Full Keyboard Access_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?fullKeyboardAccessOptions
~~~
_Accessibility > Keyboard > Sticky Keys_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_STICKY_KEYS_BEEP
~~~
_Accessibility > Keyboard > Slow Keys_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?slowKeysOptions
~~~
_Accessibility > Keyboard > Accessibility Keyboard_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_KB_APPEARANCE_TYPE
~~~
\
\
_Accessibility > Pointer Control_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?PointerControl
~~~
_Accessibility > Pointer Control > Trackpad Options_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_TRACKPAD_OPTIONS
~~~
_Accessibility > Pointer Control > Mouse Options_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_MOUSE_OPTIONS
~~~
_Accessibility > Pointer Control > Mouse Keys_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_MOUSE_KEYS_SHORTCUT
~~~
_Accessibility > Pointer Control > Alternative pointer actions_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_CONFIGURE_CAMERA
~~~
_Accessibility > Pointer Control > Head pointer_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_HEAD_MOUSE_BUTTON
~~~
\
\
_Accessibility > Switch Control_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?SwitchControl
~~~
_Accessibility > Switch Control > Switch Timing_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_SWITCH_TIMING
~~~
_Accessibility > Switch Control > Navigation Timing_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?AX_NAVIGATION_TIMING
~~~
\
\
_Accessibility > Live Speech_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?LiveSpeech
~~~
\
\
_Accessibility > Personal Voice_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?PersonalVoice
~~~
\
\
_Accessibility > Vocal Shortcuts_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?VocalShortcuts
~~~
\
\
_Accessibility > Siri_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Siri
~~~
\
\
_Accessibility > Shortcut_
~~~yaml
x-apple.systempreferences:com.apple.Accessibility-Settings.extension?Shortcut
~~~
\
\
_Appearance_
~~~yaml
x-apple.systempreferences:com.apple.Appearance-Settings.extension
~~~
\
\
_Menu Bar_
~~~yaml
x-apple.systempreferences:com.apple.ControlCenter-Settings.extension
~~~
_Menu Bar > Clock Options_
~~~yaml
x-apple.systempreferences:com.apple.ControlCenter-Settings.extension?Clock
~~~
\
\
_Apple Intelligence & Siri_
~~~yaml
x-apple.systempreferences:com.apple.Siri-Settings.extension
~~~
_Apple Intelligence & Siri > Siri Suggestions & Privacy_
~~~yaml
x-apple.systempreferences:com.apple.Siri-Settings.extension?siriSuggestions
~~~
_Apple Intelligence & Siri > Siri Suggestions & Privacy > [bundle ID of app]_
~~~yaml
x-apple.systempreferences:com.apple.Siri-Settings.extension?siriSuggestions&bundleId=replace_with_app_bundle_id
~~~
\
\
_Desktop & Dock_
~~~yaml
x-apple.systempreferences:com.apple.Desktop-Settings.extension
~~~
_Desktop & Dock > Hot Corners_
~~~yaml
x-apple.systempreferences:com.apple.Desktop-Settings.extension?HotCorners
~~~
_Desktop & Dock > Shortcuts_
~~~yaml
x-apple.systempreferences:com.apple.Desktop-Settings.extension?Shortcuts
~~~
\
\
_Displays_
~~~yaml
x-apple.systempreferences:com.apple.Displays-Settings.extension
~~~
_Displays > Advanced_
~~~yaml
x-apple.systempreferences:com.apple.Displays-Settings.extension?advancedSection
~~~
_Displays > Night Shift_
~~~yaml
x-apple.systempreferences:com.apple.Displays-Settings.extension?nightShiftSection
~~~
\
\
_Spotlight_
~~~yaml
x-apple.systempreferences:com.apple.Spotlight-Settings.extension
~~~
_Spotlight > Search Privacy_
~~~yaml
x-apple.systempreferences:com.apple.Spotlight-Settings.extension?privacy
~~~
\
\
_Wallpaper_
~~~yaml
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension
~~~
_Wallpaper > Screen Saver_
~~~yaml
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension?ScreenSaver
~~~
_Wallpaper > Clock Appearance_
~~~yaml
x-apple.systempreferences:com.apple.Wallpaper-Settings.extension?ClockAppearance
~~~
\
\
_Notifications_
~~~yaml
x-apple.systempreferences:com.apple.Notifications-Settings.extension
~~~
_Notifications > Allow Notifications from iPhone_
~~~yaml
x-apple.systempreferences:com.apple.Notifications-Settings.extension?RemoteNotifications
~~~
_Notifications > [bundle ID of app]_
~~~yaml
x-apple.systempreferences:com.apple.Notifications-Settings.extension?id=replace_with_app_bundle_id
~~~
\
\
_Sound_
~~~yaml
x-apple.systempreferences:com.apple.Sound-Settings.extension
~~~
_Sound > Output (tab)_
~~~yaml
x-apple.systempreferences:com.apple.Sound-Settings.extension?output
~~~
_Sound > Input (tab)_
~~~yaml
x-apple.systempreferences:com.apple.Sound-Settings.extension?input
~~~
\
\
_Focus_
~~~yaml
x-apple.systempreferences:com.apple.Focus-Settings.extension
~~~
\
\
_Screen Time_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension
~~~
_Screen Time > App & Website Activity <sub>when App & Website Activity is enabled</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=app-usage
~~~
_Screen Time > Notifications <sub>when App & Website Activity is enabled</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=notifications
~~~
_Screen Time > Pickups <sub>when App & Website Activity is enabled</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=pickups
~~~
_Screen Time > Downtime <sub>when App & Website Activity is enabled</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=downtime
~~~
_Screen Time > App Limits <sub>when App & Website Activity is enabled</sub>_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=app-limits
~~~
_Screen Time > Always Allowed_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=always-allowed
~~~
_Screen Time > Screen Distance_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=screen-distance
~~~
_Screen Time > Communication Limits_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=communication-limits
~~~
_Screen Time > Communications Safety_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=communication-safety
~~~
_Screen Time > Content & Privacy_
~~~yaml
x-apple.systempreferences:com.apple.Screen-Time-Settings.extension?path=content-and-privacy
~~~
\
\
_Lock Screen_
~~~yaml
x-apple.systempreferences:com.apple.Lock-Screen-Settings.extension
~~~
\
\
_Privacy & Security_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension
~~~
_Privacy & Security > Location Services_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_LocationServices
~~~
_Privacy & Security > Location Services > System Services_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_SystemServices
~~~
_Privacy & Security > Calendars_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Calendars
~~~
_Privacy & Security > Contacts_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Contacts
~~~
_Privacy & Security > Files & Folders_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_FilesAndFolders
~~~
_Privacy & Security > Full Disk Access_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AllFiles
~~~
_Privacy & Security > Home_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_HomeKit
~~~
_Privacy & Security > Media & Apple Music_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Media
~~~
_Privacy & Security > Passkeys Access for Web Browsers_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_PasskeyAccess
~~~
_Privacy & Security > Photos_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Photos
~~~
_Privacy & Security > Reminders_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Reminders
~~~
_Privacy & Security > Accessibility_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Accessibility
~~~
_Privacy & Security > App Management_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AppBundles
~~~
_Privacy & Security > Automation_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Automation
~~~
_Privacy & Security > Bluetooth_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Bluetooth
~~~
_Privacy & Security > Camera_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Camera
~~~
_Privacy & Security > Developer Tools_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_DevTools
~~~
_Privacy & Security > Focus_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Focus
~~~
_Privacy & Security > Input Monitoring_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_ListenEvent
~~~
_Privacy & Security > Microphone_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Microphone
~~~
_Privacy & Security > Motion & Fitness_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Motion
~~~
_Privacy & Security > Remote Desktop_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_RemoteDesktop
~~~
_Privacy & Security > Screen & System Audio Recording_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AudioCapture
~~~
_Privacy & Security > Speech Recognition_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_SpeechRecognition
~~~
_Privacy & Security > Sensitive Content Warning_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_NudityDetection
~~~
_Privacy & Security > Blocked Contacts_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Blocklist
~~~
_Privacy & Security > Analytics & Improvements_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Analytics
~~~
_Privacy & Security > Apple Advertising_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_Advertising
~~~
_Privacy & Security > Apple Intelligence Report_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Privacy_AppleIntelligenceReport
~~~
_Privacy & Security > Gatekeeper_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Security
~~~
_Privacy & Security > FileVault_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?FileVault
~~~
_Privacy & Security > Accessories_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Accessories
~~~
_Privacy & Security > Lockdown Mode_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?LockdownMode
~~~
_Privacy & Security > Background Security Improvements_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?SecurityImprovements
~~~
_Privacy & Security > Advanced_
~~~yaml
x-apple.systempreferences:com.apple.settings.PrivacySecurity.extension?Advanced
~~~
\
\
_Touch ID & Password_
~~~yaml
x-apple.systempreferences:com.apple.Touch-ID-Settings.extension
~~~
\
\
_Users & Groups_
~~~yaml
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension
~~~
_Users & Groups > [current user]_
~~~yaml
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo
~~~
_Users & Groups > [current user] > Password > Change_
~~~yaml
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?changepassword
~~~
_Users & Groups > [full name of user or name of user's home folder]_
~~~yaml
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo*user:replace_with_full_or_short_name_of_user
~~~
_Users & Groups > Guest User_
~~~yaml
x-apple.systempreferences:com.apple.Users-Groups-Settings.extension?showinfo*user:guest
~~~
\
\
_Internet Accounts_
~~~yaml
x-apple.systempreferences:com.apple.Internet-Accounts-Settings.extension
~~~
_Internet Accounts > Add Account_
~~~yaml
x-apple.systempreferences:com.apple.Internet-Accounts-Settings.extension?ADD_ACCOUNT
~~~
\
\
_Game Center_
~~~yaml
x-apple.systempreferences:com.apple.Game-Center-Settings.extension
~~~
_Game Center > Customize Profile_
~~~yaml
x-apple.systempreferences:com.apple.Game-Center-Settings?EDIT_PROFILE
~~~
_Game Center > All Friends_
~~~yaml
x-apple.systempreferences:com.apple.Game-Center-Settings?ALL_FRIENDS
~~~
_Game Center > Friend Requests_
~~~yaml
x-apple.systempreferences:com.apple.Game-Center-Settings?FRIEND_REQUESTS
~~~
_Game Center > Invite Friends_
~~~yaml
x-apple.systempreferences:com.apple.Game-Center-Settings?INVITE_FRIENDS
~~~
\
\
_iCloud <sub>for more URLs, see Apple Account > iCloud</sub>_
~~~yaml
x-apple.systempreferences:com.apple.systempreferences.AppleIDSettings:icloud
~~~
\
\
_Wallet & Apple Pay_
~~~yaml
x-apple.systempreferences:com.apple.WalletSettingsExtension
~~~
_Wallet & Apple Pay > Add Card_
~~~yaml
x-apple.systempreferences:com.apple.WalletSettingsExtension?fpanImportPrivacy
~~~
_Wallet & Apple Pay > AutoFill Cards_
~~~yaml
x-apple.systempreferences:com.apple.WalletSettingsExtension?autoFillPane
~~~
\
\
_AirPods [the name of your AirPods] <sub>append ‘?’ followed by the MAC address of the AirPods in case you have more than one set connected_
~~~yaml
x-apple.systempreferences:com.apple.HeadphoneSettings
~~~
\
\
_Keyboard_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension
~~~
_Keyboard > Keyboard Shortcuts > Spotlight_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?Spotlight
~~~
_Keyboard > Keyboard Shortcuts > Function keys_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?FunctionKeys
~~~
_Keyboard > Keyboard Shortcuts > Modifier keys_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?ModifierKeys
~~~
_Keyboard > Text Input > Edit_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?InputSources
~~~
_Keyboard > Text Input > Text Replacements_
~~~yaml
x-apple.systempreferences:com.apple.Keyboard-Settings.extension?TextReplacements
~~~
\
\
_Trackpad_
~~~yaml
x-apple.systempreferences:com.apple.Trackpad-Settings.extension
~~~
_Trackpad > Point & Click (tab)_
~~~yaml
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?PointAndClick
~~~
_Trackpad > Scroll & Zoom (tab)_
~~~yaml
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?ScrollAndZoom
~~~
_Trackpad > More Gestures (tab)_
~~~yaml
x-apple.systempreferences:com.apple.Trackpad-Settings.extension?MoreGestures
~~~
\
\
_Game Controllers_
~~~yaml
x-apple.systempreferences:com.apple.Game-Controller-Settings.extension
~~~
\
\
_Printers & Scanners_
~~~yaml
x-apple.systempreferences:com.apple.preference.printfax
~~~
