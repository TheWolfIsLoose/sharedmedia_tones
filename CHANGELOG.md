# Changelog

## 2.6.0

- Added a new Memes group (5 sounds, lime green): Alert, Huh, Mistakes,
  Potion, WC2 Bloodlust
- Same loudness normalization pass applied as the rest of the pack

## 2.5.4

Pipeline only — no audio changes.

- Removed the direct CurseForge-upload step from the release workflow.
  Publishing to CurseForge now happens on their side via a repository
  webhook instead of this pipeline calling their API

## 2.5.3

Metadata and release pipeline only — no audio changes.

- Linked the CurseForge project so tagged releases can publish there once
  the account API token is configured

## 2.5.2

Metadata only — no audio or packaging changes.

- Updated author attribution

## 2.5.1

Packaging fix only — no audio changes. Removed a couple of stray files that
were slipping into packaged releases.

## 2.5.0

Full rebuild from the original source recordings.

- Converted all tones from MP3 to OGG Vorbis, matching the format most other
  WoW addons use for audio
- Rebuilt from the original masters instead of re-processing already
  compressed files, for cleaner sound
- Trimmed dead air at the start and end of files so tones fire immediately
- Smoothed a handful of tones that were a little harsh or thin
- Fixed a tail click on one tone
- Rebalanced overall loudness to sit a touch more forward than 2.4.0
- Added an automated release pipeline

## 2.4.0

- Added the 26-tone Classic set alongside the existing 16 Organic tones
- Prefixed filenames `organic-` and `classic-`
- Colour-coded registrations: mint green for Organic, hot pink for Classic
- Fixed a bug in the sound file paths
- Recovered three Organic tones dropped by an earlier rebuild

## 2.3.1

- 16 Organic tones
