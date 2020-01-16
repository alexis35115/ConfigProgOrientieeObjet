# Configuration pour le cours de programmation orientiée objet

La configuration exprimée ici est pour une machine de développement sous Windows! Toutefois, il serait envisageable d'utiliser Visual Studio Code comme alternative pour éditer le code.

## Visual Studio 2019

### Installation

Pourquoi Visual Studio 2019? C'est la dernière version disponible et la version "community" offre tout ce dont nous avons besoin dans le cadre du cours.

1. Valider la présence de Visual Studio 2019 sur votre machine, si ce n'est pas le cas, procédez à l'installation de [Visual Studio 2019](https://visualstudio.microsoft.com/fr/vs/).
2. Ouvrir "Visual Studio Installer"
   1. Cliquez sur "Modifier" pour Visual Studio 2019.
   2. Assurez-vous que "Développement .Net Desktop" et "Développement multiplateforme .NET Core" soient sélectionnées, si ce n'est pas le cas, sélectionnez-les et cliquez sur "Modifier" dans le coin inférieur droit.
3. Ouvrez une invite de commandes PowerShell, exécutez la commande "dotnet --version". La version de .Net devrait être >= à 3.1.

### Extensions à installer

- [Add New File](https://marketplace.visualstudio.com/items?itemName=MadsKristensen.AddNewFile)
- [Productivity Power Tools 2017/2019](https://marketplace.visualstudio.com/items?itemName=VisualStudioPlatformTeam.ProductivityPowerPack2017)
- [Indent Guides](https://marketplace.visualstudio.com/items?itemName=SteveDowerMSFT.IndentGuides)
- [Visual Studio Spell Checker (VS2017 and Later)](https://marketplace.visualstudio.com/items?itemName=EWoodruff.VisualStudioSpellCheckerVS2017andLater)

## Git

Git sera le contrôleur de code source utilisé dans le cadre du cours.

Valider la présence de Git sur votre poste via la commande "git --version" dans une invite PowerShell.

Effectuer la configuration initiale, si besoin : <https://git-scm.com/book/fr/v2/D%C3%A9marrage-rapide-Param%C3%A9trage-%C3%A0-la-premi%C3%A8re-utilisation-de-Git>.

## Visual Studio Code

Si vous n'avez pas Visual Studio 2017+ sur votre poste, vous aurez à installer le SDK et le runtime. Voir la page <https://dotnet.microsoft.com/download/dotnet-core/3.1>.

Voici quelques extensions :

- [C#](https://marketplace.visualstudio.com/items?itemName=ms-vscode.csharp)
- [C# Extensions](https://marketplace.visualstudio.com/items?itemName=jchannon.csharpextensions)
- [C# XML Documentation Comments](https://marketplace.visualstudio.com/items?itemName=k--kato.docomment)
- [Auto-Using for C#](https://marketplace.visualstudio.com/items?itemName=Fudge.auto-using)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [Visual Studio Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.vs-keybindings)
- [Guides](https://marketplace.visualstudio.com/items?itemName=spywhere.guides)
- [Git Lens](https://gitlens.amod.io/)
