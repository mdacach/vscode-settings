# vscode-settings
settings for vscode json file and extensions list 

# install extensions on vscode 
cat vs_code_extensions_list.txt | xargs -n 1 code --install-extension

# remove all existing extensions
code --list-extensions | xargs -n 1 code --uninstall-extension
