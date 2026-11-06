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
