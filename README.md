# cloud-Restaurant
realisation de ce tp a l'aide de framework springboot+ langage de programation kotlin+bootstrap materiel design
on a 4 packages: Repository,service,entity,routes
-package entity contient: classe en Kotlin qui contient 3fields :rate->float(1-5) ;liste->raete;libelle
-package Repository:classe kotlin qui fait la creation de liste de restaurant importé de fichier (restaurant.json)qui se trouve dans le dossier data
-package service: restaurant -service: passage de liste de restaurant au html(thymeleaf fait bridge entre springboot et html)
package routes:responsable de gestion de routage en html si un client met le lien localhost:9999/rate "/rate" spring boot va executer les requettes venu de cet url et il va regenerer une nouvelle liste (apres avoir fait update les rates de restaurant) et il envoi une reponse au client dans cet url("/rate")
pour le coté design(html):contient 3 dossiers:data->liste de restaurant dans un fichier json;template->page index.html; gestion coté html faite par thymeleaf(html template en spring boot)

![sans titre](https://user-images.githubusercontent.com/25961912/47390565-8eaa5480-d6cc-11e8-9fef-f6aa5f3846db.png)


vous trouvez dans mon compte Anfel1990 le projet complet(parceque quand je voulais faire upload dans repertoire de team"BerrehailBoudoudaAnfelBounouiouaSawsen" ça m'affiche dossier hidden pour 3 dossiers alors avec application github desktop 'ete simple j'ai pu tout publier)parceque j'ai télécharger et utiliser github desktop->file->create repository remplir name et description cocher readme,mettre le projet dans le chemin de dossier creer puis commit et publish apres je vais ouvrir mon compte en navigateur wwww.github.com je cree un team et j'ai invité les membres puis j'ai recréee repository avec meme etapes precedentes
au faite j'avais un compte github depuis un bail je me suis rentré sur le lien: www.github.com signin et voila email et mode passe et j'ai creer compte apres validation de email le compte est pret a utiliser.
![sans titre4](https://user-images.githubusercontent.com/25961912/47389797-8d782800-d6ca-11e8-9aae-fef5741ee643.png)
 
 En ce qui concerne le openShift j'ai ouvert un compte dedans www.openshift.com j'ai creer un projet avec item Redhat openjdk8.1.1 j'ai rempli avec le nom de projet'restaurant-cloud'et application name"jdk" et en gitrepository" https://github.com/BerrehailBoudoudaAnfelBounouiouaSawsen/AppWeb.git" ->create 
 ![sans titre7](https://user-images.githubusercontent.com/25961912/47390395-252a4600-d6cc-11e8-9863-10e1bd6e1e8e.png)
 ![sans titre8](https://user-images.githubusercontent.com/25961912/47390477-59056b80-d6cc-11e8-8081-4d0b0a0fcef2.png)

 
 build->logs :on verra le telechargement de tout les dependance de projets on attend le telechargement jusqu'a tout les jar sont upload dans le directory 
 ![cloud2](https://user-images.githubusercontent.com/25961912/47389271-345bc480-d6c9-11e8-9240-6366edf47a86.png)

 
 overview->pods:pourvoir voir execution de notre projet sur github
 ![openshift](https://user-images.githubusercontent.com/25961912/47389396-7c7ae700-d6c9-11e8-9192-8ad4b15c3090.png)

 overview ->click sur le link :excutuion de app sur navigateur
 
![sans titre3](https://user-images.githubusercontent.com/25961912/47389657-36725300-d6ca-11e8-88d6-43117e0197dc.png)
 
pour le travail demandé coté implimentation moi"berrehail boudouda anfel" et mon binome "Bounouioua sawsen" on a fait tout ensemble on a pas partagé travail entre nous seulement elle ,elle a beaucoup concentré sur le design et moi je fais de plus configuration de github desktop et creation de repertoire et upload etout 
