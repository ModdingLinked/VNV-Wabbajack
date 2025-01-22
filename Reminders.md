### During dev
- Delete the base profile, only work on the extended one.
- Keep the mods ordered just like in the guide.
- Add comments if any mod are more involved in their use (through the MO2 notes column), e.g. how using the Stewie Tweaks VNVE config has gameplay implications.
- When updating mods, take note of which have been updated and to what version. You can do this by batch selecting after checking updates on all mods with MO2. Then write down the new version for each and use it for the update's changelog.
- Try not to change contents of any mod and/or including big files that patch vanilla ones. This will inflate the WJ file due to delta patching.
- Use The Method for the load order conflict resolution.
- Enable archive parsing and disable MO2's GUI lock for an easier time.

### Right before upload
- Update the date separator.
- Decompress plugins.
- Restore the game's folder to totally vanilla.
- Remove any exe you added during development from MO2's executables list.
- Remove uninstalled mods from the download pane (it's a right-click function).
- Go in the profile folder and delete all the old backups, then recreate them (both mod list and load order).
- Copy the profile and turn it into the extended one deleted at the start, then obviously disable all the mods that aren't part of the base guide.
- If you used any new executable, make sure to remove them from the bottom of ModOrganizer.ini.
- Make sure the load order is correct, MO2 likes to push non-ESM plugins near the top further up sometimes.
- Take the load order file for upload to the guide's resources page on Nexus, don't forget to add any missing plugins to the file itself. Currently it should just be EVEM - Uncut Extra Collection Patch and EVEM - FPGE Patch (because the guide uses the merged option).

### During upload
- Update the version to dd.mm.yy.
- Update the author to ModdingLinked for the first new upload after moving repos.
- Remove all Modgroups from the included files, then batch add them by filtering the extension in Explorer.
- Preferably make a test version with the upload option unchecked at first, then upload once it's confirmed to be working and that all the previous notes have been followed.
