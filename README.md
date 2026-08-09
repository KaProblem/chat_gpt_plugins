# JGPD Plugins

Codex-Plugins von KaProblem e.U.

## Marketplace installieren

```bash
codex plugin marketplace add KaProblem/chat_gpt_plugins
```

Danach können die enthaltenen Plugins einzeln installiert werden.

## Verfügbare Plugins

### sharewise

Verbindet Codex über OAuth mit [sharewise](https://www.sharewise.com/). Damit lassen sich Wertpapiere suchen, Community-Einschätzungen abrufen sowie Watchlists, Prognosen und Musterdepots verwalten.

```bash
codex plugin add sharewise@jgpd
```

Beim ersten Zugriff meldet sich jeder Nutzer mit seinem eigenen sharewise-Konto an und bestätigt die angeforderten Berechtigungen. Das Plugin enthält keine Zugangsdaten oder Tokens.

## Aktualisieren

```bash
codex plugin marketplace upgrade jgpd
codex plugin add sharewise@jgpd
```

Nach einer Installation oder Aktualisierung sollte ein neuer Codex-Task gestartet werden, damit die aktuelle Plugin-Version geladen wird.

## Struktur

```text
.agents/plugins/marketplace.json  Marketplace-Katalog
plugins/sharewise/               sharewise-Plugin
```
