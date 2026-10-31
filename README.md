# Zsh configuration

Oh My Zsh, Autosuggestions, Syntax-Highlighting, FZF, zoxide und Shell-Helfer.

**[Vollständige Dokumentation](https://arch-dotfiles.readthedocs.io/en/latest/shell/)** ·
[Komponenten](https://arch-dotfiles.readthedocs.io/en/latest/components/#zsh) ·
[Installation und Updates](https://arch-dotfiles.readthedocs.io/en/latest/arch-package/)

```bash
curl -fsSL https://raw.githubusercontent.com/MichaelWeissDEV/dotfiles/main/install.sh | bash -s -- zsh
```

Paket: `arch-dotfiles-zsh`. Dateien: `~/.config/zsh/zshrc`, `aliases.zsh` und `themes/`.
`~/.zshrc` wird bei der Aktivierung gesichert und verlinkt. Login-Shell und
Systemdienste werden nicht automatisch geändert. Alle Aliase stehen im Handbuch.

Hier unabhängig auf `main` pushen; nach erfolgreichem Registry-Build mit
`sudo pacman -Syu` aktualisieren. [PACKAGING.md](PACKAGING.md).

### Anpassung

Einstieg ist `~/.config/zsh/zshrc`; Aliase stehen in `aliases.zsh`. Änderungen in einer neuen Shell testen. Die Login-Shell wird nicht automatisch umgestellt; die Shell-Anleitung erklärt die vorhandenen Helfer.

Eigene Änderungen in der aktivierten Benutzerkopie bleiben bei der Synchronisierung erhalten; neue abweichende Vorgaben erscheinen als `.pacnew`. Siehe [Update und Wiederherstellung](https://arch-dotfiles.readthedocs.io/en/latest/verification/).

[![Package safety](https://github.com/MichaelWeissDEV/zsh-config/actions/workflows/package.yml/badge.svg)](https://github.com/MichaelWeissDEV/zsh-config/actions/workflows/package.yml)

[MIT-Lizenz](LICENSE).
