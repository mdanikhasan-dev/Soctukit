# SoctuKit

<p align="center">
  <img src="https://raw.githubusercontent.com/mdanikhasan-dev/Soctukit/main/assets/soctukit-banner.png" alt="SoctuKit banner" width="100%" />
</p>

<p align="center">
  <strong>Desktop workspace for account connection, live visibility, drafting, and publishing.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%20%2F%2011-0F6CBD?style=flat-square&logo=windows&logoColor=white" alt="Windows support badge" />
  <img src="https://img.shields.io/badge/Desktop-WinUI%203-111827?style=flat-square" alt="Desktop app badge" />
  <img src="https://img.shields.io/badge/Build-Setup%20EXE-2563EB?style=flat-square" alt="Build badge" />
  <img src="https://img.shields.io/badge/License-Proprietary-F97316?style=flat-square" alt="License badge" />
  <img src="https://img.shields.io/badge/Publisher-Sawlper-0F172A?style=flat-square" alt="Publisher badge" />
</p>

<p align="center">
  <a href="https://github.com/mdanikhasan-dev/Soctukit/raw/main/SoctuKitSetup.exe">
    <img src="https://img.shields.io/badge/Get%20the%20Installer-SoctuKitSetup.exe-2563EB?style=for-the-badge&logo=github&logoColor=white" alt="Installer download button" />
  </a>
  <a href="https://github.com/mdanikhasan-dev/Soctukit/raw/main/SoctuKitSetup.exe.sha256.txt">
    <img src="https://img.shields.io/badge/Verify-SHA--256-0F766E?style=for-the-badge" alt="Checksum button" />
  </a>
  <a href="https://github.com/mdanikhasan-dev/Soctukit/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/View-License-E11D48?style=for-the-badge" alt="License button" />
  </a>
  <a href="https://mdanikhasan.com">
    <img src="https://img.shields.io/badge/Open-Official%20Website-111827?style=for-the-badge" alt="Website button" />
  </a>
</p>

<p align="center">
  <a href="#overview">Overview</a> |
  <a href="#preview">Preview</a> |
  <a href="#features">Features</a> |
  <a href="#platform-support">Platform Support</a> |
  <a href="#download">Download</a> |
  <a href="#safety-and-privacy">Safety</a> |
  <a href="#support">Support</a>
</p>

## Overview

SoctuKit is the desktop app I built to keep the workflow in one place instead of bouncing between browser tabs, dashboards, and scattered tools.

The idea is simple:

- connect accounts from one workspace
- check the current state quickly
- move from topic to draft faster
- keep publishing flow inside one desktop app

This repository is the public release page for the app. The source code is not included here.

All images in this README use public URLs, so the same content can be pasted into a website and still render the banner and previews correctly.

## Preview

The hero banner above already uses a real desktop build screenshot from the app. Below are the additional in-app previews you kept for the release page.

### Accounts

<p align="center">
  <img src="https://raw.githubusercontent.com/mdanikhasan-dev/Soctukit/main/assets/previews/accounts-preview.png" alt="SoctuKit accounts preview" width="96%" />
</p>

Connect platforms, reconnect sessions, or disconnect saved access from one place.

### Settings

<p align="center">
  <img src="https://raw.githubusercontent.com/mdanikhasan-dev/Soctukit/main/assets/previews/settings-preview.png" alt="SoctuKit settings preview" width="96%" />
</p>

Control appearance, tray behavior, and startup behavior without extra Windows setup work.

## Features

### What SoctuKit does

- Manage supported platforms from one desktop workspace
- Show dashboard analytics, reach, and activity in one app
- Help move from account selection into content flow with less friction
- Keep theme, startup, and tray behavior inside the app
- Ship as a real setup EXE instead of exposing the full development structure

### Workflow

1. Connect accounts
2. Check current visibility and dashboard state
3. Move into draft and content flow
4. Publish from the same desktop workspace

## Platform Support

| Platform | Sign-in | Publish | Notes |
|---|---|---|---|
| X / Twitter | Working | Working | Requires your own app setup |
| LinkedIn | Working | Working | Requires client ID, client secret, and callback setup |
| Reddit | Coming soon | Coming soon | Not finished in this build yet |
| Facebook | Coming soon | Coming soon | Not finished in this build yet |
| Instagram | Coming soon | Coming soon | Not finished in this build yet |

## Download

Main release files:

- `SoctuKitSetup.exe`
- `SoctuKitSetup.exe.sha256.txt`

SHA-256:

`B76ED217C5B298DD0FAFCC316FB781DDF9D4C26E71D1AA4BBE5FE60D95365B6D`

Direct links:

- Release page: `https://github.com/mdanikhasan-dev/Soctukit/releases/tag/v1.0.0`
- Installer: `https://github.com/mdanikhasan-dev/Soctukit/releases/download/v1.0.0/SoctuKitSetup.exe`
- Checksum: `https://github.com/mdanikhasan-dev/Soctukit/releases/download/v1.0.0/SoctuKitSetup.exe.sha256.txt`
- License: `https://github.com/mdanikhasan-dev/Soctukit/blob/main/LICENSE`

## Setup Notes

- `OPENAI_API_KEY` gives stronger AI generation
- X and LinkedIn each need your own developer app setup before sign-in works properly
- Reddit, Facebook, and Instagram are better described as coming soon in this public build

## Safety And Privacy

### What Is Already Good

- This public repo does not include the source code
- OAuth tokens are stored in Windows Credential Manager
- Saved platform app secrets stay on the local machine
- The app is distributed as a proper Windows installer

### What Users Should Still Know

- Windows may still show a trust warning until the app uses a publicly trusted code-signing certificate
- Downloads should only come from the official GitHub repo or official website
- No desktop app can be made impossible to reverse engineer, so confidential secrets should never be shipped in the client app

## License

SoctuKit is free to use, but it is not open source.

You may not:

- modify it
- redistribute it
- rebrand it
- resell it
- reverse engineer it
- decompile it
- claim it as your own work

Full license:

`https://github.com/mdanikhasan-dev/Soctukit/blob/main/LICENSE`

## Support

<p align="center">
  <a href="https://mdanikhasan.com">
    <img src="https://img.shields.io/badge/Website-mdanikhasan.com-0F172A?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website badge" />
  </a>
  <a href="mailto:anikhasan2@iCloud.com">
    <img src="https://img.shields.io/badge/Email-anikhasan2%40iCloud.com-2563EB?style=for-the-badge&logo=gmail&logoColor=white" alt="Email badge" />
  </a>
</p>

- Developer: `Md Anik Hasan`
- Company: `Sawlper`
- Website: `https://mdanikhasan.com`
- Email: `anikhasan2@iCloud.com`

## Short Description

SoctuKit is a Windows desktop social publishing workspace for account connection, live visibility, drafting, and publishing flow.
