# BDDClientTD 
<<<<<<< HEAD
>>>>>>> 28c5a4fdb6d4adc86b7a84f0cb398e1f73f74cc2

Liste des requêtes possibles :</br>
<ol>API GitHub
    <li>
        <ul>
            <li>Partage de projet</li>
            <li>Evènement sur les projets open source les plus populaires</li>
            <li>Commentaire sur les projets</li>
            <li>Suivis sur les projets personnels (statistique)</li>
            <li>Alerte sur les issues</li>
        </ul>
    </li>
API Météo :
    - Afficher la météo locale
    - Afficher la météo dans un lieu désiré
    - Alertes météos
    - Météo par heures/Jours/semaines
    - Afficher les précipitations
    </ol>

2) API Choisi : GitHub

3) Requête POST :

curl --user "Kaweet" --data '{"description":"Created via API","public":"true","files":{"README.md":{"content":"TEST"}}' https://github.com/Kaweet/BDDClientTD1/

curl --data "login=Kaweet" --data "token=TOKEN" https://github.com/api/v2/json/user/show/Kaweet

4) Requete GET :
curl https://api.github.com/users/Kaweet

curl --user "Kaweet:PASSWD" https://api.github.com/gists/starred

</ol>