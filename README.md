# PFA
# Instructions pour tester le code
Pour tester ce code, vous devez suivre les étapes suivantes :
#
-Assurez-vous d'avoir installé XAMPP et activé Apache et MySQL.
#
-Utilisez Git Bash pour cloner notre application dans le répertoire XAMPP/htdocs/dossier (où "dossier" est le nom d'un dossier vide de votre choix). Assurez-vous d'avoir installé Git Bash sur votre système, puis ouvrez-le et accédez au répertoire souhaité à l'aide de la commande "cd chemin/vers/le/répertoire". Ensuite, exécutez la commande "git clone <URL_du_dépôt>" en remplaçant "<URL_du_dépôt>" par l'URL du dépôt GitHub contenant l'application à cloner. Git Bash commencera alors à télécharger les fichiers de l'application dans le répertoire spécifié. Pour accéder à l'application, assurez-vous que XAMPP est en cours d'exécution, puis ouvrez votre navigateur et entrez "localhost/dossier/php" dans la barre d'adresse. Ainsi, vous pourrez utiliser notre application en accédant à cette URL dans votre navigateur.
#
-Accédez à PHPMyAdmin et exécutez en sql  le fichiers dont le chemin d'accès est "pfa/db/database(1).db". Cela préparera la base de données pour une utilisation ultérieure.
#
-vous pouvez accéder maintenant a notre application en ut
-Pour vous connecter en tant que pépiniériste, cliquez sur "Sign Up" situé en haut à droite et créez votre compte en choisissant si vous êtes une personne physique ou morale.
#
-Une fois inscrit, vous pouvez effectuer une déclaration en cliquant sur "Nouvelle Déclaration", puis choisissez le nombre de variétés et cliquez sur "Entrer". Des champs à remplir apparaîtront en fonction du nombre de variétés entrées.
#
-Après avoir enregistré votre déclaration, vous pouvez suivre le processus de contrôle en vous connectant à l'application. Consultez la boîte de messagerie pour voir les notifications sur la conformité des contrôles. Chaque étape du processus sera colorée en bleu si elle est effectuée, sinon elle restera grise.
#
-Une fois que tous les contrôles ont été effectués et sont conformes, un bouton de demande d'ACP/LP apparaîtra. En cliquant dessus, vous devrez entrer le nombre de variétés déclarées, puis cliquer sur "Entrer" et remplir les autres champs qui apparaîtront.
#
-Si les informations saisies sont correctes, une fenêtre d'impression apparaîtra. Sinon, une fenêtre indiquant qu'il faut refaire la demande s'affichera. Vous pouvez vous déconnecter à tout moment en cliquant sur "Logout" en haut de la page.
#
-En tant qu'agent contrôleur, vous pouvez vous connecter en utilisant les informations suivantes : nom d'utilisateur : "yuki", mot de passe : "1234", type : "agent". Cela vous permettra de consulter la liste des déclarations enregistrées. Choisissez une déclaration en fonction de l'ID du pépiniériste et remplissez le formulaire de contrôle correspondant en cliquant sur "Formulaire à remplir" en haut de la page.
#
-Si un contrôle n'est pas conforme, vous serez redirigé vers un autre formulaire où le contrôle sera refait. Sinon, vous serez redirigé vers le formulaire du contrôle suivant. Une fois un résultat saisi, il sera directement envoyé à la boîte de messagerie du pépiniériste associé, et la valeur "État" correspondante à la déclaration en cours de suivi sera mise à jour.
#
-Vous pouvez naviguer entre les déclarations comme vous le souhaitez. Pour vous déconnecter, cliquez sur "Logout" en bas de l'icône de l'administrateur.
#
-De plus, vous pouvez accéder à la page principale à tout moment en cliquant sur le logo de l'application situé en haut à gauche de la page.
