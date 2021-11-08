# Setup VSCode for Flutter

## Extensions

- Flutter and Dart extensions 
- Bracket Pair Colorizer 2
- Material Icon Theme
- Better comments
- bloc  (Felix Angelov)
- Todo tree
- Pubspec assist (cmd+Shift+P  then pubspec assist)
- Flutter Intl
- Color Highlight
- Image Preview

You may install fvm 

## Theme 
- Monokai Theme, of gerane

Remove default Monokai theme : https://stackoverflow.com/questions/67480448/remove-sublime-text-theme-in-vscode

## Snippet

Code > Settings > Preferences > User Snipper > select ```dart```
```json
{
	 "Import AppLocalisation": {
	 	"prefix": "import applocalization",
	 	"body": [
	 		"import 'package:flutter_gen/gen_l10n/app_localizations.dart';",
	 	],
		"description": "Import generated app_localizations file"
	 },
	 "AppLocalisation Text": {
		"prefix": "applocalization",
		"body": [
			"AppLocalizations.of(context)!.$1"
		],
	   "description": "AppLocalizations.of(context)!.$1"
	},
	"kIsWeb import": {
		"prefix": "import kisWeb",
		"body": [
			"import 'package:flutter/foundation.dart' show kIsWeb;"
		],
	   "description": "kIsWeb import"
	},
	"l10n": {
		"prefix": "l10n",
		"body": [
			"import 'package:chanel_replica_show/generated/l10n.dart';"
		],
	   "description": "l10n"
	},
	"intl": {
		"prefix": "intl",
		"body": [
			"import 'package:intl/intl.dart';"
		],
	   "description": "intl"
	},
	"log": {
		"prefix": "log",
		"body": [
			"Log get log => Log.get(runtimeType.toString());"
		],
	   "description": "log"
	},
	"tz": {
		"prefix": "tz",
		"body": [
			"import 'package:timezone/timezone.dart' as tz;"
		],
	   "description": "tz"
	}

}
```

## Shortkey

- Multicursor : press alt and click

- Name refactoring :
fn+F2+name of the class/function for example, or put the actual code of a Text widget inside a Column widget
or ctrl+Shift+R

- Formatting text :
Select a text , Shift+alt(option)+F

- Code folding, fermer des div ou autre avec :
   - fermer avec : alt+cmd+[
-  ouvrir avec : alt+cmd+]

- Flutter run with the bar : (fn) +  f5

- Pubspec assist : cmd+Shift+P then pubspec assist

## VSCode Settings

- Set the line length at 120

In VSCode : Code > Settings > "Dart line length" > 120

## Tools for Mac


### Configure internet access of your Mac/iPhone simulator to 3G
- https://medium.com/macoclock/ios-simulator-simulates-slow-network-connection-615f910a2f43<br/>
- https://developer.apple.com/download/more/?=for%20Xcode<br/>
- Download Additional_Tools_for_Xcode then install Hardware > Network Link Conditioner.prefPane


## In terminal, use code

in .zshrc : 
```
export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
// For below, different if using fvm
export PATH="$PATH:/Users/dle/Documents/Flutter/Software/flutter/bin" <br/>
export PATH="$PATH:/Applications/Sublime Text.app/Contents/SharedSupport/bin" <br/>
```
