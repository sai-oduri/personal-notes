1. `Close and Quit VSCode`
2. `Remove VScode from Applications (just go to Finder -> Applications and move VSCode to Bin)`

3. Execute these commands in any order. The paths might be slightly different for you. 
```
rm -fr ~/.vscode*
rm -fr ~/Library/Application\ Support/Code/

rm -fr ~/Library/Saved\ Application\ State/com.microsoft.VSCode.savedState/
rm -fr ~/Library/Preferences/com.microsoft.VSCode.helper.plist 
rm -fr ~/Library/Preferences/com.microsoft.VSCode.plist 
rm -fr ~/Library/Caches/com.microsoft.VSCode
rm -fr ~/Library/Caches/com.microsoft.VSCode.ShipIt/
```

4. `Reinstall VSCode`
