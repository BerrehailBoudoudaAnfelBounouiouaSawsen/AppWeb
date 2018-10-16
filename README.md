# cloud-Restaurant
realisation de ce tp a l'aide de framework springboot+ langage de programation kotlin+bootstrap materiel design
on a 4 packages: Repository,service,entity,routes
-package entity contient: classe en Kotlin qui contient 3fields :rate->float(1-5) ;liste->raete;libelle
-package Repository:classe kotlin qui fait la creation de liste de restaurant importé de fichier (restaurant.json)qui se trouve dans le dossier data
-package service: restaurant -service: passage de liste de restaurant au html(thymeleaf fait bridge entre springboot et html)
package routes:responsable de gestion de routage en html si un client met le lien localhost:9999/rate "/rate" spring boot va executer les requettes venu de cet url et il va regenerer une nouvelle liste (apres avoir fait update les rates de restaurant) et il envoi une reponse au client dans cet url("/rate")
pour le coté design(html):contient 3 dossiers:data->liste de restaurant dans un fichier json;template->page index.html; gestion coté html faite par thymeleaf(html template en spring boot)


vous trouvez dans mon compte Anfel1990 le projet complet(parceque quand je voulais faire upload dans repertoire de team"BerrehailBoudoudaAnfelBounouiouaSawsen" ça m'affiche dossier hidden pour 3 dossiers alors avec application github desktop 'ete simple j'ai pu tout publier)parceque j'ai télécharger et utiliser github desktop->file->create repository remplir name et description cocher readme,mettre le projet dans le chemin de dossier creer puis commit et publish apres je vais ouvrir mon compte en navigateur wwww.github.com je cree un team et j'ai invité les membres puis j'ai recréee repository avec meme etapes precedentes
au faite j'avais un compte github depuis un bail je me suis rentré sur le lien: www.github.com signin et voila email et mode passe et j'ai creer compte apres validation de email le compte est pret a utiliser.



pour le travail demandé coté implimentation moi"berrehail boudouda anfel" et mon binome "Bounouioua sawsen" on a fait tout ensemble on a pas partagé travail entre nous seulement elle ,elle a beaucoup concentré sur le design et moi je fais de plus configuration de github desktop et creation de repertoire et upload etout 
