# Installation & Troubleshooting

## Requirements

- Call of Duty: Black Ops 4 on PC
- Shield Client
- Zombies mode

## Install

1. Close Black Ops 4.
2. Download `PermanentProgression-v1.0.0.zip`.
3. Extract the archive.
4. Move the `PermanentProgression` folder into:

   ```text
   C:\Call of Duty Black Ops 4\project-bo4\mods\
   ```

5. Verify:

   ```text
   C:\Call of Duty Black Ops 4\project-bo4\mods\PermanentProgression\metadata.json
   C:\Call of Duty Black Ops 4\project-bo4\mods\PermanentProgression\compiled.gscc
   ```

6. Launch BO4 through Shield Client.
7. Enter Zombies.
8. Confirm **PERMANENT UPGRADES** appears.

## Updating

For a clean update:

1. Close BO4.
2. Back up the old `PermanentProgression` folder if desired.
3. Delete the old folder.
4. Copy in the new release folder.

Avoid merging old RC/test files into a new stable release.

## Uninstall

Close BO4 and remove:

```text
C:\Call of Duty Black Ops 4\project-bo4\mods\PermanentProgression
```

## Troubleshooting

### PERMANENT UPGRADES does not appear

- Confirm `metadata.json` exists directly inside `PermanentProgression`.
- Confirm you did not accidentally create:

  ```text
  PermanentProgression\PermanentProgression\
  ```

- Cold-start BO4 after replacing mod files.

### UI or script error

Include your Shield `project-bo4.log` with the issue report.

### BO4 Enhancement

Enhancement compatibility is not supported by the standalone v1.0.0 release. Do not install old development compatibility RC packages with the public release.
