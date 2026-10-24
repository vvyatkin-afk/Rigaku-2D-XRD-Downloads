# Rigaku 2D XRD — Windows Downloads

This public repository distributes **Windows binaries only**. The XRD source repository remains private.

## Recommended: v4.0.2 Portable

[Download v4.0.2 Portable ZIP](https://github.com/vvyatkin-afk/Rigaku-2D-XRD-Downloads/releases/download/v4.0.2/Rigaku_2D_XRD_v4.0.2_PORTABLE.zip) · [SHA-256 file](https://github.com/vvyatkin-afk/Rigaku-2D-XRD-Downloads/releases/download/v4.0.2/Rigaku_2D_XRD_v4.0.2_PORTABLE.sha256)

**Installation:** Right-click ZIP → **Extract All / Извлечь все**. Open the entire extracted folder and double-click Rigaku_2D_XRD_v4.0.2.exe. Keep the _internal folder beside the EXE. Do **not** run from inside ZIP or copy only the EXE. A Russian readme is included.

The 4.0.2 Windows portable package passed all 63 automated tests, Windows SciPy sparse/Excel/plotting self-test, GUI startup, and re-test after extracting the ZIP into a Unicode folder. The XRD processing algorithms match the v4.0.1 source, whose numerical regressions included three real Batch 10 RASX scans. A complete 143-scan reprocessing on the user's Windows system and parity to v3 are still unverified.

## Previous v4.0.1

The old one-file v4.0.1 EXE can fail before the GUI starts with a PyInstaller decompression error for scipy/sparse/_csparsetools.pyd. It is marked as a legacy prerelease and should **not** be chosen over v4.0.2.
