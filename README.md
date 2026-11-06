# Habit Tracker – downloads

Habits, tasks, projects, notes, a calendar and a focus timer in one app.

**[Download the latest version](https://github.com/MrJackyYT/habit-tracker-releases/releases/latest)**

| Device  | File                      |
|---------|---------------------------|
| Android | `HabitTracker.apk`        |
| Windows | `Habit-Tracker-Setup.exe` |
| Linux   | `Habit-Tracker.deb` (Ubuntu, Debian, Mint …) or `Habit-Tracker.AppImage` |
| macOS   | `Habit-Tracker-mac.dmg` (Intel and Apple silicon) |
| iPhone / iPad | no file – the web app: **[mrjackyyt.github.io/habit-tracker-releases](https://mrjackyyt.github.io/habit-tracker-releases/)** |

**Updates:** from version 1.6 on, the app on Windows and Linux updates itself – it downloads a new version in the
background and installs it when you close it. On Android press *Update* in the app and confirm *Update this app?*.
On macOS the app shows when a new version is out – download the new `.dmg` and replace the app (your data stays).
The web app (iPhone) is always the newest version.

**Where is my data?** Only on your device. On a computer it is also kept in the folder **Documents › Habit Tracker**
(Settings → Data → Open folder). To move it to another device use Settings → Data → Export backup / Import backup.

**Windows:** run the setup and follow the steps. It adds Habit Tracker to the Start menu and the desktop. For a new
version run the new setup – your data stays.

**Android:** open the downloaded file and allow installing from this source. Google Play Protect may warn because the app
is not from the Play Store – choose *Install anyway*.

**Linux:** the `.deb` installs like any other app (open it, or `sudo apt install ./Habit-Tracker.deb`) and adds Habit Tracker
to the app menu. The `.AppImage` needs no installing: make the file executable (right click → Properties → Allow executing,
or `chmod +x Habit-Tracker.AppImage`) and open it.
If it does not start, what it printed is in `~/.cache/habit-tracker-start.log`.

**macOS:** open the `.dmg` and drag Habit Tracker into *Applications*. The app is not signed with an Apple certificate,
so the first time macOS says it cannot check it: open *System Settings → Privacy & Security*, scroll down and press
*Open Anyway* (or right click the app → *Open*). If it still says the app is damaged, run
`xattr -cr "/Applications/Habit Tracker.app"` in Terminal once.
Focus blocking asks for your Mac password when a session starts and stops (it changes the system's hosts file).

**iPhone / iPad:** open **[mrjackyyt.github.io/habit-tracker-releases](https://mrjackyyt.github.io/habit-tracker-releases/)**
in **Safari**, press *Share* (the square with the arrow) → *Add to Home Screen* → *Add*. Habit Tracker then opens from
the home screen like an app, full screen and also without internet. Your data stays on the iPhone – don't delete the
web app's data in Safari settings, and make a backup now and then (Settings → Data → Export backup).
On iPhone, focus blocking of other apps is not possible, and reminders show only while the app is open.
