# LangeVC Homebrew Tap

Public Homebrew Formulae maintained by LangeVC.

## AI Engineering Ledger

```bash
brew tap langevc/tap
brew install ael
ael doctor
ael ui
```

`ael ui` opens the local browser interface for source setup, reviewed imports,
dashboard snapshots and reports. Tesseract is a recommended dependency for
local PNG screenshot OCR; every extracted value still requires explicit review
before it enters the ledger. Install the manual-review workflow without OCR via
`brew install --without-tesseract ael`.

Upgrade with:

```bash
brew update
brew upgrade ael
```

AEL keeps its local database, protected inbox, evidence, exports and backups in
Homebrew's persistent `var/lib/ael` directory. `brew uninstall ael` does not
delete those user-owned data files.

The Formula consumes an immutable, checksummed release archive from the public
[AI Engineering Ledger mirror](https://github.com/LangeVC/ai-engineering-ledger).

## License

Each Formula retains the license of its upstream project. AEL is Apache-2.0.
