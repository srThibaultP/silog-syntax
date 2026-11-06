# SILOG Syntax Highlighting

Coloration syntaxique pour les fichiers SILOG (`.evt` et `.act`) de l'ERP Silog.

## Fonctionnalités

- Blocs : `[SI]`, `[ALORS]`, `[SINON]`, `[TANTQUE]`, `[CONDITION]`, `[POURCHAQUE]`, `[EXTRAIRE]` et leurs `[FIN…]`
- Fonctions de paramétrage (`SAM`, `SER`, `SEA`, `SilExecuterRequete`…), fichiers, répertoires, chaînes, `MAIL.*`
- Fonctions mathématiques et de chaînes (`LEFT$`, `MID$`, `ROUND`…)
- Variables : `vu()`, globales `g_*`, `m_Table.Champ`, `Table.Champ`, `@variable` dans les requêtes SQL
- Commentaires `//`, chaînes `"…"` et `'…'`
- Snippets (`si`, `tantque`, `pourchaque`, `sam`, `ser`…)
- Repli des blocs et fermeture automatique des parenthèses et guillemets

## Licence

MIT

## Développement et publication

La CI GitHub Actions (`.github/workflows/ci.yml`) valide les JSON et génère le `.vsix` à chaque push et pull request (artefact `silog-syntax-vsix`).

Pour publier une version :

1. Mettre à jour `version` dans `package.json` et le `CHANGELOG.md`.
2. Ajouter le secret `VSCE_PAT` (jeton Azure DevOps, scope *Marketplace → Manage*) dans *Settings → Secrets and variables → Actions*.
3. Créer et pousser le tag : `git tag v0.1.0 && git push origin v0.1.0`.

Le workflow publie alors sur le Marketplace et crée une release GitHub avec le `.vsix`.
