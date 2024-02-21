# Using the Installer

## Installing Updates

1. Run the Installer (requires read, write and execute permissions).
2. Set the settings you want with the `set` command:
    - `changes_file <path>` (No quotes required for path): Set the path to the JSON file containing the changes.
      Defaults to the JSON file in the same
      folder as the Installer, if it exists.
    - `game_directory <path>` (No quotes required for path): Set the path to the root game directory. Defaults to the
      Installer's grandparent folder (
      should place the folder containing the new game files in the root game directory).
    - `files_directory <path>` (No quotes required for path): Set the path to the root directory containing the new game
      files. Defaults to the parent
      folder of the Installer.
    - `create_backup <(t)rue|(f)alse>`: Set whether to create a backup of the original files before installing. Defaults
      to `true`. Backups will be stored in the `.Backup` directory in the `game_directory`.
    - `copy_files <(t)rue|(f)alse>`: Set whether the new game files will be copied over. Defaults to `true`. Disable
      this option if you want to only remove files (cleanup the game directory) based on the `changes_file`.
    - `remove_files <(t)rue|(f)alse>`: Set whether the old game files, specified in the `changes_file`, will be removed.
      Defaults to `true`.
3. After confirming the settings, type `update` to start the installation of the new game files.
4. After the installation is complete, type `exit` to exit the Installer.

## Creating Updates

The Installer can also be used to extract files from a game directory as well by reversing the installation process.
This is useful for users who have a local copy of the game and want to create updates based of that.

1. Follow steps 1-3 for [getting the changes](Using-the-Creator.md), or alternatively, create the JSON file manually (
   not recommended).
2. Set the `changes_file` to the new JSON file containing the changes.
3. Set the `files_directory` to the root game directory.
4. Set the `game_directory` to the new folder you want to extract the files to.
5. Type `update` to extract the files.
6. The `changes_file` and Installer will have to be manually copied over to the new update folder.
