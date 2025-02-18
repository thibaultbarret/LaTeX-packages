# Overview 
- Packages sur mesures pour utiliser des commandes depuis n'importe quel repertoire
    - `MMC.sty` : package pour écrire des éléments de mécaniques des milieux continus : tenseur des contraintes, des déformatios ...
    - `dic.sty` : package pour écrire les élements liés à la corrélation d'image numérique 
    - `tikzpgfplots.sty` : package qui regroupe `tikz` et `pgfplots` ainsi que les librairies associées. Les styles pour les noeuds, les tracés ... sont définis dans les fichiers `.tex`

# Utilisation 
- Copier les fichiers dans le repertoire d'installation de la distribution latex : `/usr/local/texlive/texmf-local/tex/latex/local`
- Executer la commande `sudo texhash`
- Les packages peuvent être appelés `\usepackage{MMC}`
