# PianoToMidi privacy policy

Effective September 13, 2026

PianoToMidi is an Android app that records or imports piano audio, prepares a local transcription draft, and exports MIDI. This policy applies to the PianoToMidi app and its developer, who publishes this policy under the GitHub account `deanyjones`. For privacy questions, [open an issue in the policy repository](https://github.com/deanyjones/pianotomidi-privacy/issues). The developer's public support email will also appear on the app's Google Play listing.

## Audio access

The app asks for microphone permission when you choose to start recording. Recording continues until you stop it. If you leave the app during an active recording, Android shows a foreground-service notification so you can return and stop capture. You may instead select an existing audio file through Android's file picker. The app reads the file you select and makes a local WAV copy for transcription; it does not change the original.

## Processing and storage

PianoToMidi transcribes audio on your device. Recording WAV files, imported WAV copies, note edits, tempo, and session state are kept in app-specific storage. When you choose **Save MIDI**, the app writes a `.mid` file to `Music/MIDI` using Android's media storage. Other apps on your device may access that exported file. Temporary import staging files are removed after conversion.

## Collection and sharing

PianoToMidi does not send your audio, MIDI, or app activity to the developer or a server. The app has no account, ads, or analytics. It does not sell or share your data with the developer or third parties. If you use Android or another app to share an exported file, that action is under your control and the receiving app's privacy practices apply.

## Protection and deletion

Working files are in Android's app-specific storage, protected by the Android app sandbox. The app disables cloud and device-transfer backup. You can delete the current recording when starting a new one. If you choose to keep a recording, or import audio, local copies may remain until you clear PianoToMidi's app storage or uninstall the app. Exported MIDI files in `Music/MIDI` remain after that and must be deleted separately. The original audio file you selected remains wherever you stored it.

This policy will be updated if the app's data practices change. The effective date above will change when the policy is revised.
