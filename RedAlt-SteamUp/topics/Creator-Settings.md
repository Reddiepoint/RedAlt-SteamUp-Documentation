# Settings

## Depot Downloader Settings

- Username/password: Your Steam username and password.
- Remember credentials: Allows Depot Downloader to remember your password/Steam Guard code.
    - Your username will be saved to `settings.json`, encrypted with AES256-GCM with XOR encryption and the key will be
      stored in `key.json`.
    - Your username will be automatically loaded when you start RedAlt SteamUp Creator.
- Max number of server connections: The maximum number of content servers to use.
- Max number of concurrent chunks: The maximum number of chunks to download concurrently.

## Compression Settings

- Compression settings for 7-zip/WinRAR

## MultiUp Direct Settings

- Path: The path to the MultiUp Direct executable.

## Create Update Settings

- Target OS: The target operating system for the installation of the update (chooses which Installer to include with the
  update files).
- Ignore changes and download entire depot: If enabled, the entire depot with the specified manifest for the final build
  will be downloaded. The Installer and changes file will not be included.
- Download manifest: If enabled, the specified manifest will be downloaded. Note that this is not the
  original `.manifest` file, but a readable version provided by Depot Downloader.
    - The manifest file will be either in the `.RedAlt-SteamUp-Installer` folder or in the root directory if the ignore
      changes option is enabled.
    - Depot Downloader will create a new folder named `depots` which you can delete.
- Compress files after downloading: If enabled, the downloaded files will be compressed with the settings specified in
  the  [compression settings](#compression-settings).

## Resetting Settings

- To reset the settings to their default values, delete the `settings.json` file and `key.json` file.
- You can also delete the specified entry in the JSON file to reset it to its default value, but be careful that it is
  still valid JSON.