# How to Build Pirate Island.app

## Prerequisites
- QB64 (Phoenix Edition recommended)
- `pirate.icns` icon file

## Steps

1. Open `pirate_island_qb64.bas` in QB64
2. Compile with **Run → Make EXE / .app only** (or just Make Executable Only)
3. Create a folder named `Pirate Island.app`
4. Inside it, create this structure:
```
Pirate Island.app/
└── Contents/
├── MacOS/
│   └── pirate_island_qb64          ← your compiled executable
├── Resources/
│   └── pirate.icns                 ← your icon
└── Info.plist                      ← see below
```

5. Create `Contents/Info.plist` with this content:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
    <key>CFBundleName</key>
    <string>Pirate Island</string>
    <key>CFBundleIdentifier</key>
    <string>com.m-endymion.pirateisland</string>
    <key>CFBundleVersion</key>
    <string>1.0</string>
    <key>CFBundleShortVersionString</key>
    <string>1.0</string>
    <key>CFBundleExecutable</key>
    <string>pirate_island_qb64</string>
    <key>CFBundleIconFile</key>
    <string>pirate.icns</string>
    <key>CFBundlePackageType</key>
    <string>APPL</string>
</dict>
</plist>
```
6. Right-click the .app folder → Get Info → drag your pirate.icns onto the top-left icon to force it.

You now have a proper macOS application!
