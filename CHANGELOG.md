# Changelog

## 0.1.0
- Grammaire enrichie d'après la documentation SILOG : fonctions `Sil*` et leurs abréviations (SAM, SER, SEA…), fonctions de fichiers/répertoires/chaînes, `MAIL.*`, `NOTIFICATIONS.*`, `KRN.*`, fonctions mathématiques et de chaînes (`LEFT$`, `ROUND`…).
- Variables : `vu()`, globales `g_*` / `p_*`, valeurs avant modification `m_Table.Champ`, champs `Table.Champ`, variables `@var` dans les requêtes SQL.
- Opérateurs `AND`, `OR`, `NOT`, comparaisons, nombres, chaînes entre `'` et `"`.
- Correction : `\` n'est plus traité comme caractère d'échappement (chemins Windows).
- Snippets pour `[SI]`, `[TANTQUE]`, `[POURCHAQUE]`, `SAM`, `SER`.
- Repli (folding) des blocs `[SI]…[FINSI]`, `[POURCHAQUE]…[FINPOURCHAQUE]`, etc.

## 0.0.1
- Première version : coloration syntaxique SILOG.
