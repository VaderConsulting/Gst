# Gst

Chips, Bits and Bytes VB6 GST Tool (`GST.exe`) for product pricing with Australian GST. Searches ADO-bound rows, then calculates GST-inclusive sell price from buy price, GST tax rate, and markup (Tools: Randomize / Calculate). UI caption "GST Tool"; OCXs: `MSADODC.OCX`, `MSCOMCTL.OCX`, `MSDATGRD.OCX`.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Project1` (`Gst.vbp`) | VB6 | WinForms exe | GST price calculator over ADO product rows |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Gst.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `MSADODC.OCX`
  - `MSCOMCTL.OCX`
  - `MSDATGRD.OCX`

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Gst`.
Company names in project files: Chips, Bits and Bytes.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
