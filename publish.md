git pu Setup la première fois:
 1. Générer un access token sur https://dev.azure.com/altevo/
 2. npm install -g @vscode/vsce 
 3. vsce login TeamAltevo
 4. Coller le access token de https://dev.azure.com/altevo/
 

 Ensuite, à chaque fois qu'une nouvelle version doit être publiée, il suffit de suivre les étapes suivantes :
 - Incrémenter la version dans le fichier `package.json`
 - vsce package 
 - vsce publish