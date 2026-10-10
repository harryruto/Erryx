# ERRYX

**ERRYX — C Error Diagnostic Assistant**

ERRYX est un outil en ligne de commande développé en C qui aide les développeurs à comprendre les erreurs courantes de programmation. Il fournit des explications claires sur les messages d'erreur, leur signification et les pistes possibles pour les résoudre.

## 🇫🇷 Français

### Présentation

ERRYX a pour objectif de rendre le diagnostic des erreurs en C plus accessible, notamment pour les développeurs débutants.

Grâce à une bibliothèque de diagnostics, le programme permet de rechercher des messages d'erreur connus et de consulter leur signification ainsi que des conseils de correction.

### Fonctionnalités

- **Diagnostic des erreurs :** rechercher et identifier les messages d'erreur reconnus.
- **Explications détaillées :** comprendre la signification d'un message.
- **Conseils de correction :** obtenir des pistes pour résoudre un problème.
- **Bibliothèque de diagnostics :** consulter les erreurs répertoriées.
- **Interface console :** utiliser le programme sans interface graphique.
- **Évolutivité :** ajouter progressivement de nouveaux diagnostics.

> Les diagnostics proposés dépendent de la base de connaissances intégrée au programme. ERRYX ne garantit pas la détection de toutes les erreurs ni la correction automatique du code.

### Technologies utilisées

- **Langage :** C
- **Interface :** console
- **Compilation :** GCC ou un compilateur C compatible
- **Bibliothèques :** bibliothèque standard du C, selon les fonctionnalités implémentées

### Compilation

Avec GCC, compile le programme depuis le terminal :

```bash
gcc -Wall -Wextra -std=c11 main.c -o erryx
```

Cette commande suppose que le point d'entrée du programme se trouve dans `main.c`. Si le projet contient plusieurs fichiers sources, ajoute-les à la commande de compilation.

### Exécution

Sous Linux ou macOS :

```bash
./erryx
```

Sous Windows :

```powershell
.\erryx.exe
```

### Utilisation

1. Lance ERRYX.
2. Choisis une option dans le menu.
3. Saisis le message d'erreur à analyser ou consulte la bibliothèque.
4. Lis la signification et les pistes de correction proposées.

Les options disponibles dépendent de la version installée.

### Limites

ERRYX est un outil d'assistance au diagnostic. Il ne remplace ni un compilateur, ni un débogueur, ni une analyse complète du programme.

Les messages des compilateurs peuvent varier selon leur version et leurs options. Un message non reconnu peut nécessiter une analyse manuelle.

---

## 🇬🇧 English

### Overview

ERRYX is a C-based command-line tool designed to help developers understand common programming errors.

It uses a diagnostic knowledge base to explain recognized error messages, describe their meaning, and suggest possible troubleshooting steps.

### Features

- **Error diagnostics:** search for recognized error messages.
- **Clear explanations:** understand what an error means.
- **Troubleshooting guidance:** receive suggestions for investigating a problem.
- **Diagnostic library:** browse known errors.
- **Console interface:** operate without a graphical user interface.
- **Extensible knowledge base:** add new diagnostics over time.

> ERRYX can only diagnose messages covered by its implemented knowledge base. It does not guarantee complete error detection or automatic code correction.

### Technologies

- **Language:** C
- **Interface:** command line
- **Compiler:** GCC or another compatible C compiler
- **Libraries:** the C standard library, depending on the implemented features

### Compilation

Using GCC:

```bash
gcc -Wall -Wextra -std=c11 main.c -o erryx
```

This command assumes that the program's entry point is in `main.c`. Add any additional source files required by your project.

### Running ERRYX

On Linux or macOS:

```bash
./erryx
```

On Windows:

```powershell
.\erryx.exe
```

### Usage

1. Start ERRYX.
2. Select an option from the menu.
3. Enter an error message or browse the diagnostic library.
4. Read the explanation and suggested troubleshooting steps.

Available options depend on the installed version.

### Limitations

ERRYX is a diagnostic assistant, not a replacement for a compiler, debugger, or comprehensive code analysis tool.

Compiler messages may vary across versions and configurations. Unrecognized messages may require manual investigation.

---

## Project status

**Status:** Initial development

ERRYX is intended to grow through the gradual addition of diagnostics, explanations, and troubleshooting guidance.

## License

No license has been specified yet. Until a license is added to the repository, permissions to redistribute or modify the project should not be assumed.

## Author

Developed as a C programming project focused on error diagnostics and developer assistance.
