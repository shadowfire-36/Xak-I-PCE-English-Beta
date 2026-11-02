# Xak I — PC Engine CD English Beta 1

An experimental English playtest patch for **Xak I** on the Japanese **Xak I & II** PC Engine CD disc. **Xak II is not included in this translation beta.**

## Download

[Download the Beta 1 patch ZIP](https://github.com/shadowfire-36/Xak-I-PCE-English-Beta/raw/refs/heads/main/Xak_I_English_Beta_1.zip)

Use [Delta Patcher](https://github.com/marco-calautti/DeltaPatcher/releases) to apply the included xdelta patch to a **copy** of your matching original raw disc image. No game image or BIOS is included.

[Step-by-step installation](INSTALLATION.txt) · [Checksums](CHECKSUMS.json) · [Report a bug](https://github.com/shadowfire-36/Xak-I-PCE-English-Beta/issues)

## Required image

Whole-disc RAW image with 2352-byte sectors; **563,057,040 bytes**. A CHD, separate-track set or 2048-byte ISO is not this input; changing an extension does not convert it.

| Image | CRC32 |
|---|---|
| Exact original | `6BD28D3D` |
| Patched Beta 1 | `EC14DA90` |

Full SHA-256 values are in the instructions and checksums file. Keep checksum validation enabled in your patcher.

## Beta scope and limits

The exported source register contains 1,169 Japanese/English pairs spanning dialogue, shop text, equipment labels and system messages. This is source coverage, **not proof of a full natural playthrough**.

- A complete natural playthrough and every choice branch are not verified.
- **Normal in-game saving needs testing.** Saving stalled from an imported cave snapshot in both older and beta builds. Private Mesen save-state creation/reload passed. Back up saves and report problems.
- Japanese cinematic audio and movie staff-credit graphics remain unchanged.
- Actual hardware compatibility is not verified by the private emulator tests.

## Testing help wanted

Please report untranslated text, clipping, wrong speakers, crashes, save problems or progression blockers. Include emulator/version, scene, screenshot, reproduction steps and an optional save state. Avoid posting game images or BIOS files.

## Credits

**Original MSX English translation: Rieks Warendorp Torringa.**

PC Engine adaptation and beta project: **Jason / shadowfire-36**. The MSX script served as a reference, with PCE-specific differences handled separately. This independent beta is not a WOOMB-authored or endorsed PCE release; exact extracted-script edition identification remains under review.

## Screenshots

![Beta cave gameplay](screenshots/cave-gameplay.png)

![English Fire Elemental dialogue](screenshots/4e22b2.png)

![English Rockbiter dialogue](screenshots/4e2bbf.png)

The cave capture is a loaded beta gameplay checkpoint. The two dialogue images are native renderer tests captured with Beta 1, not evidence of naturally reached story progression.

