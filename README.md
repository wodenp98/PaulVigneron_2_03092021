Reservia

![image](https://user-images.githubusercontent.com/81572285/168854930-daf8269f-cecb-465b-8220-6cd506446bca.png)



Note de synthèse – Nouveau site
Booki
Voici l’ensemble des points techniques et fonctionnels à prendre en
compte pour le développement du nouveau site Booki. L’ensemble de ces
éléments ont été validés par l’équipe Produit, il est donc important de les
respecter.
Spécifications fonctionnelles
● Les usagers pourront rechercher des hébergements dans la ville de
leur choix. Le champ de recherche est un champ de saisie, le texte
doit donc pouvoir être édité par l’utilisateur. Il faut englober ce
champ dans un formulaire pour que ce dernier soit valide auprès du
W3C. La partie recherche ne doit pas être fonctionnelle.
● Chaque carte d’hébergement ou d’activité devra être cliquable dans
son intégralité (pas uniquement le titre). Pour l’instant, les liens sont
vides. On peut utiliser un attribut `href=”#”` pour simuler la
présence d’un lien.
● Les filtres doivent changer d’apparence au survol. Je te laisse décider
de l’effet approprié, je n’ai pas encore eu le temps de me pencher
dessus. Par contre, ils ne doivent pas être fonctionnels.
● Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont
des liens. Ils doivent mener respectivement vers la section
“Hébergements à Marseille” et “Activités à Marseille”.
Spécifications techniques
● Deux maquettes ont été réalisées : l’une desktop et l’autre mobile. Le
site devra être également adapté aux formats tablette. Pour les
tablettes, nous sommes libres de faire les adaptations nécessaires. Il
est important qu’aucun élément ne soit coupé, et que le texte ait
une taille suffisante.
● Concernant les breakpoints, nous avons convenu avec le designer UI
d’utiliser 992 px et 768 px.
992 px pour les écrans d’ordinateurs et 768 px pour les tablettes, et
tout ce qui est en dessous de 768 pour les téléphones portables.
● Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement
dit, en desktop first), puis les tablettes et enfin les téléphones.
