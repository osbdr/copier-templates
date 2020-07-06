# Copier Templates

copier: https://github.com/copier-org/copier

Dieses Repository kann sowohl für neue und bestehende Projekte genutzt werden. Es beinhaltet grundlegende Konfigurationsdateien für:

- GitHub Actions

- GitHub Templates

- Renovate

- Semantic Versioning

> Für die Nutzung wird Python 3 benötigt.

## Anleitung

Zunächst `pipx` und `copier` installieren:

```bash
pip install pipx
pipx install copier
```

Zum Initialisieren eines neuen Projekts:

```bash
copier https://github.com/osbdr/copier-templates.git <PROJEKT_ORDNER>
```

Zum Aktualisieren eines Projekts:

```bash
cd <PROJEKT_ORDNER>
copier update
```
