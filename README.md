# ERRYX

**ERRYX — C Syntax Error Assistant**

ERRYX is a command-line program written in C that helps developers understand common C syntax errors.

The project is currently in its early development stage and focuses exclusively on recognizing and explaining selected syntax errors.

## 🇫🇷 Français

### Présentation

ERRYX est un assistant en console conçu pour aider les développeurs, notamment les débutants, à comprendre les erreurs de syntaxe en C.

L'utilisateur saisit un message d'erreur et ERRYX recherche les motifs qu'il reconnaît afin de fournir une explication simple.

### Fonctionnalités actuelles

- Interface en console avec affichage coloré sous Windows.
- Saisie d'un message d'erreur.
- Reconnaissance de certains messages liés à la syntaxe.
- Explication des erreurs reconnues.

### Erreurs prises en charge

La première version vise notamment les erreurs suivantes :

| Message d'erreur | Explication |
|---|---|
| `expected ';' before ...` | Un point-virgule est attendu. |
| `expected ')' before ...` | Une parenthèse fermante est attendue. |

La reconnaissance dépend des motifs effectivement implémentés dans le code.

### Technologies

- **Langage :** C
- **Interface :** console
- **Système ciblé actuellement :** Windows
- **API de console :** Windows API (`windows.h`)
- **Bibliothèques :** bibliothèque standard du C

### Compilation

Avec GCC sous Windows, compile le fichier source à l'aide de MinGW-w64 :

```bash
gcc -Wall -Wextra -std=c11 main.c -o erryx.exe
```

Remplace `main.c` par le nom de ton fichier source si nécessaire.

### Exécution

Dans un terminal Windows :

```powershell
.\erryx.exe
```

### Limites actuelles

ERRYX est encore en développement.

- Seules certaines erreurs de syntaxe sont prises en charge.
- Les messages non reconnus ne disposent pas encore d'un diagnostic dédié.
- Les erreurs de types, les erreurs de liaison, les avertissements et les erreurs d'exécution ne sont pas encore prises en charge.
- Le programme explique les messages reconnus, mais ne corrige pas automatiquement le code source.

### Évolutions prévues

Les prochaines versions pourront intégrer progressivement :

- De nouvelles erreurs de syntaxe.
- Une meilleure reconnaissance des messages provenant de différents compilateurs.
- Les erreurs de variables et de types.
- Les erreurs de fonctions et d'édition de liens.
- Les avertissements et les problèmes d'exécution.

Ces fonctionnalités restent prévues et ne sont pas annoncées comme disponibles.

---

## 🇬🇧 English

### Overview

ERRYX is a C command-line application designed to help developers understand common C syntax errors.

The project is currently in its early development stage and focuses exclusively on recognizing and explaining selected syntax errors.

### Current features

- Colored console output on Windows.
- Error message input.
- Recognition of selected syntax-related messages.
- Simple explanations for recognized errors.

### Currently supported errors

| Error message | Explanation |
|---|---|
| `expected ';' before ...` | A semicolon is expected. |
| `expected ')' before ...` | A closing parenthesis is expected. |

Recognition depends on the patterns actually implemented in the source code.

### Technologies

- **Language:** C
- **Interface:** command line
- **Current target platform:** Windows
- **Console API:** Windows API (`windows.h`)
- **Libraries:** C standard library

### Compilation

Using GCC with MinGW-w64 on Windows:

```bash
gcc -Wall -Wextra -std=c11 main.c -o erryx.exe
```

Replace `main.c` with the name of your source file if necessary.

### Running ERRYX

In a Windows terminal:

```powershell
.\erryx.exe
```

### Current limitations

ERRYX is still under development.

- Only selected syntax errors are supported.
- Unrecognized messages do not yet have dedicated diagnostics.
- Type errors, linker errors, warnings, and runtime errors are not yet supported.
- The program explains recognized messages but does not automatically fix source code.

### Planned improvements

Future versions may introduce additional syntax diagnostics, broader compiler-message recognition, variable and type errors, function errors, linker errors, warnings, and runtime diagnostics.

These features are planned and are not yet available.

---

## Project status

**Status:** Early development

## License

No license has been specified yet. Redistribution and modification permissions should not be assumed until a license is added.

## Author

Developed as a C programming project focused on syntax-error diagnostics.
