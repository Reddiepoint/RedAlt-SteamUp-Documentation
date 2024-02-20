# Introduction

This documentation provides help
for [RedAlt SteamUp Creator](https://github.com/Reddiepoint/RedAlt-Steam-Update-Creator)
and [RedAlt SteamUp Installer](https://github.com/Reddiepoint/RedAlt-Steam-Update-Installer).

## What is RedAlt SteamUp?

RedAlt SteamUp provides users with a convenient alternative for creating and installing Steam updates without the need
for xDelta patches. It downloads the files changed between builds, listed in the SteamDB changelist, with Depot
Downloader. Updates created using RedAlt SteamUp Creator allow for updating from any build between the specified initial
build, to the final build. For example, if the update was created for Build 10000000 to Build 10000010, then the update
would be compatible with builds 10000000-10000009 (although some files would be redundant).

The RedAlt SteamUp Installer is bundled with the update for easy installation with support for either copying or
removing (or both) files, and is able to back up the files before installing. The RedAlt SteamUp Installer can also be
used to create updates from local files, allowing users to create updates for games that they may not own on Steam, but
have a local copy available.
