# Deleting Steam Credentials

Steam Credentials are managed by Depot Downloader, and are stored in `%localappdata%/IsolatedStorage`, as well as the
username being stored in `settings.json`.

To remove any stored credentials, delete this folder, and delete the `encrypted_username` field from `settings.json`.