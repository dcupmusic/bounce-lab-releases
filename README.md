# Bounce Lab

A Mac player for comparing song versions at matched loudness, with waveform alignment, timestamped comments and song to-dos.

## Install

Requires an **Apple Silicon Mac running macOS 14 or later**.

1. [Download the latest release](https://github.com/dcupmusic/bounce-lab-releases/releases/latest) and open **BounceLab-0.5.0.dmg** (or the DMG for the newest version).
2. Drag **Bounce Lab** into **Applications**.
3. Open Bounce Lab from Applications.
4. Choose the locally synced Dropbox folder containing your song projects.
5. In Library settings, set the shared bounce-folder name if it differs from `Bounces`.

The app is Developer ID signed and notarized by Apple. The loudness engine is included; no separate installation is needed.

## Updates

Automatic update checking and installation are enabled in the release build. Manage them under **Bounce Lab → Settings**, or use **Bounce Lab → Check for Updates…** for an immediate check. New versions must be built and published by the maintainer; this release repository does not independently generate app updates.

## Collaborate through Dropbox

Both people need the app and the same shared song project folders downloaded locally in Dropbox. Comments, replies, task links, resolutions and completions are recorded in each song's `.bouncelab` metadata folder and synced by Dropbox. Keep that folder alongside the audio. Delivery depends on Dropbox; the app reads incoming edits every three seconds. Display names can be set in Library settings.

This public repository contains app downloads and the signed update feed. Your music and review data are not uploaded here by Bounce Lab.
