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

On VSCode > Preferences > Settings> dart.runPubGetOnPubspecChanges > false

You may have to use RVM if problem with pods

## Theme 
- Monokai theme

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

## Tools for Mac


### Configure internet access of your Mac/iPhone simulator to 3G
- https://medium.com/macoclock/ios-simulator-simulates-slow-network-connection-615f910a2f43<br/>
- https://developer.apple.com/download/more/?=for%20Xcode<br/>
- Download Additional_Tools_for_Xcode then install Hardware > Network Link Conditioner.prefPane


## In terminal, use code

in .zshrc : <br/>
export PATH="$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin" <br/>
export PATH="$PATH:/Users/dle/Documents/Flutter/Software/flutter/bin" <br/>
export PATH="$PATH:/Applications/Sublime Text.app/Contents/SharedSupport/bin" <br/>
