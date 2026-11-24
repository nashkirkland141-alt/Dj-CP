# CP Soundboard (auto-detecting sound pads)

## Add sounds
1. Put MP3, WAV, OGG, M4A, or AAC audio files in `app/src/main/assets/sounds/`.
2. Commit/push the files to GitHub.
3. Run the **Build CP Soundboard APK** workflow (Actions → workflow → Run workflow), or push to `main`.
4. The build automatically generates the sound list from that folder. Every audio file becomes a button, named from its filename.

No edits to HTML or JavaScript are needed when adding sounds. The APK is built with sounds bundled in, so adding files requires rebuilding/reinstalling the APK; installed APKs cannot directly read repository folders.

## Build
GitHub Actions builds a debug APK and uploads it as `CP-Soundboard-APK`.
