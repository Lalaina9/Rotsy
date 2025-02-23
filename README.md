Last login: Sun Feb 23 17:44:57 on ttys000
lalaina@MacBook-Air-de-Toloranjanahary ~ % # Créer le dossier principal
mkdir mon_site

# Créer les sous-dossiers
mkdir mon_site/images
mkdir mon_site/HTML

# Créer les fichiers HTML vides
touch mon_site/HTML/index.html
touch mon_site/HTML/histoire_voitures.html
touch mon_site/HTML/trains.html
zsh: command not found: #
mkdir: mon_site: File exists
zsh: command not found: #
mkdir: mon_site/images: File exists
mkdir: mon_site/HTML: File exists
zsh: command not found: #
lalaina@MacBook-Air-de-Toloranjanahary ~ % # Copier les images depuis leurs emplacements actuels vers le dossier images
cp /Users/lalaina/Downloads/voiture_apparat.jpg mon_site/images/
cp /Users/lalaina/Downloads/voiture_comte.jpg mon_site/images/
cp /Users/lalaina/Downloads/tableau.png mon_site/images/
zsh: command not found: #
lalaina@MacBook-Air-de-Toloranjanahary ~ %  # Télécharger l'animation GIF dans le dossier images
cd mon_site/images
wget https://archive.org/download/lesmerveillesdel00deha/lesmerveillesdel00deha.gif -O animation.gif
cd ../..  # Revenir au dossier parent
quote> # Télécharger l'animation GIF dans le dossier images
cd mon_site/images
wget https://archive.org/download/lesmerveillesdel00deha/lesmerveillesdel00deha.gif -O animation.gif
cd ../..  # Revenir au dossier parent
zsh: command not found: #
zsh: command not found: wget
cd: too many arguments
lalaina@MacBook-Air-de-Toloranjanahary images % >....                           
    <h1>Les chemins de fer</h1>

    <!-- Texte -->
    <p>Voici un tableau représentant l'évolution des chemins de fer :</p>

    <!-- Tableau -->
    <table border="1">
        <tr>
            <th>Année</th>
            <th>Événement</th>
        </tr>
        <tr>
            <td>1825</td>
            <td>Premier train à vapeur</td>
        </tr>
        <tr>
            <td>1850</td>
            <td>Expansion des réseaux ferroviaires</td>
        </tr>
    </table>
</body>
</html> # Compresser le dossier mon_site en un fichier ZIP
zip -r Prenom_Nom.zip mon_site
zsh: event not found: DOCTYPE
lalaina@MacBook-Air-de-Toloranjanahary images % # Compresser le dossier mon_site en un fichier ZIP
zip -r rotsy_toloranjanahary mon_site
zsh: command not found: #
	zip warning: name not matched: mon_site

zip error: Nothing to do! (try: zip -r rotsy_toloranjanahary . -i mon_site)
lalaina@MacBook-Air-de-Toloranjanahary images % zip -r rotsy_toloranjanahary . -i mon_site
	zip warning: zip file empty
lalaina@MacBook-Air-de-Toloranjanahary images % 
