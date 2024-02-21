# Using the Creator

1. Install
   the [SteamDB Changelist Grabber script](https://github.com/Reddiepoint/RedAlt-SteamUp-Creator/blob/main/RedAlt-SteamDB-Changelist-Grabber.user.js)
   with a script manager.
2. Go to game's patchnotes page (https://steamdb.info/app/`APPID`/patchnotes/)
3. Click the `Get changes` button and specify the depot ID and the build numbers that you want to create an update for.
    - The script will open a window for each build. Wait for the script to finish and the changes will be downloaded as
      a JSON file.
4. Check for updates in the Creator and update the Installer (or download them manually).
5. Open the JSON file in the Creator and confirm the changes and settings you want to use.
    - Login with your Steam account details. You will be prompted with a request for a Steam Guard code if you have it
      enabled.
    - Make sure to save your settings after you change them!
6. Choose the Target OS. This will determine which Installer will be bundled with the downloaded files.
7. There is the option to download the entire depot (the Installer will not be bundled in this case), and an option to
   compress the files after downloading.
    - Disable the compression option if you intend to modify the files after downloading (such as applying a crack, but
      if you add more files, they will need to be updated in the bundled JSON file containing the changes).
8. Click the `Download changes` button to download the files.
9. Share the files!