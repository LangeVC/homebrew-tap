# LangeVC Homebrew Tap

Public Homebrew Formulae maintained by LangeVC.

## AI Engineering Ledger

```bash
brew tap langevc/tap
brew install ael
ael doctor
```

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
