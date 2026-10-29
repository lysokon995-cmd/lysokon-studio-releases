# Lysokon Studio · Releases

Installers and signed updates for Lysokon Studio on macOS and «Новый» on Windows.

[Download the latest release](https://github.com/lysokon995-cmd/lysokon-studio-releases/releases/latest)

- macOS 14+: `Lysokon-Studio-Mac.zip` (Apple Silicon and Intel)
- Windows 10/11 x64: `Новый.exe`

Each device keeps its own tasks, assistant memory and model cache. Personal data is not synchronized or included in release assets. The application uses a local Ollama runtime; model weights are downloaded on first assistant setup.

Automatic updates verify the signed `update-manifest.json` with the embedded Ed25519 public key, then verify the asset size and SHA-256. Private source and release signing keys are stored separately.

The Windows workflow verifies a draft installer before publication. Its fixtures are synthetic and use an isolated runner profile.
