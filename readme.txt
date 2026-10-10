Bienvenue sur mon site : AcheteTonFilm

Le concept est simple : il s'agit d'un site e-commerce centré / axé sur l'achat de film, au formats physiques (DVD, Blu-Ray, Blu-Ray 4K.

Comme demandé dans le cahier des charges, il est totalement complet et respecte absolument tout ce qui est demandé.

--------------------------------------

D'abord, parlons de la page d'accueil.

    1.
        Elle contient une barre de navigation entièrement fonctionnelle :
            - le logo de mon site qui est plus là pour l'aspect visuel / design du site mais qui renvoie vers la page d'accueil lorsqu'il est cliqué.
            - le texte cliquable "Accueil" qui renvoie également vers la page d'accueil.
            - le texte cliquable "Catégories" qui renvoie vers la section Catégorie dans la page d'accueil.
            - le texte cliquable "Catalogue" qui renvoie vers la section Catalogue dans la page d'accueil.
            - le texte cliquable "Support" qui renvoie vers la page Suport de mon site.
            - le logo du panier qui est présent pour l'aspect visuel / design du site mais qui renvoie quand même vers la section catalogue
            lorsqu'il est cliqué.

    2.
        Le premier bloc de la page d'accueil contient des textes d'accueil, ayant pour but de donner envie à l'utilisateur de parcourir
        l'entièreté du site. A droite de ces textes, on peut retrouver une image de promo du site, qui zoome un peu au survol. Elle amène
        du design et elle a pour but de présenter en quelque sorte le site et de donner envie de le parcourir.

    3.
        On arrive ensuite à la section Catégories. Elle regroupe les 4 panneaux correspondants aux quatre catégories de films disponibles
        sur mon site : Fantasy, Science-Fiction, Thriller, et Comédie. Ces panneaux sont cliquables et s'agrandissent au survol pour plus
        d'interactivité. Cela modernise le site. En cliquant sur ces panneaux, on atterrit respectivement sur la page catégorie du panneau
        sur lequel on a cliqué.

    4.
        Après, il y a la section Catalogue. Cette section présente des exemples de films, en l'occurence tous les films disponibles sur mon
        site. On peut voir leurs titres sous leurs affiches. Toutes les affiches et leurs titres sont cliquables, et renvoient vers la page
        consacrée au film cliqué.

    5.
        Enfin, cette page d'accueil dispose d'un footer qui regroupe mes informations et qui propose également différentes façons de me
        contacter, en cliquant sur mon numéro de téléphone pour m'appeler par exemple ou encore en cliquant sur mon mail pour m'envoyer un mail
        (le lien envoie directement sur votre application de messagerie mail en créant un mail qui s'envoie vers mon adresse mail
        (philipponneaumorgan@gmail.com). Le footer regroupe également les liens vers toutes les pages spécifiques de catégories, ainsi que vers
        la page support. Il y a aussi mon adresse de résidence, la ville dans laquelle j'habite et mon code postal.

--------------------------------------

Deuxièmement, parlons des pages produits, soit les pages de films. J'ai voulu faire des pages originales, et le rendu me plaît énormément.
Chaque page à la même forme. Elles se composent de :
    - La force de la page : un fond de page variable :
        J'ai utilisé l'animation CSS @keyframes changeBackground, qui me permet de changer de fond d'écran autant de fois que je le souhaite
        sur une durée définie. Cette animation m'a permis, pour chaque page de film, d'amener de l'originalité, en choisissant 3 images pour
        chaque film, comme demandé dans le cahier des charges. Dans l'animation, la durée max correspond à 100%, donc sur une certaine quantité
        de %, je mets un fond. Sur une autre, un autre fond, etc... et je répète cela à l'infini avec "infinite" dans le css.

    - Navbar semblable à celle de la page d'accueil, avec les mêmes fonctionnalités.
    - La boîte de produit, qui, comme demandé, contient le titre du produit ; le synopsis du film en guise de
      description ; sa durée, sa note en étoiles (référence : Allociné) et son genre comme caractéristiques du produit ;
      ainsi que sa boîte d'achat qui contient les différents formats avec les prix associés (disposés sous forme de liste
      <ul>, son statut, par défaut sur "Actuellement Disponible", qui indique que le produit est en stock, et le bouton
      "Acheter" qui, si on le clique, renvoie vers la page d'accueil index.
    - Une section "Produits Recommandés", qui recommande au visiteur du site des films en bas de la page de chaque film, comme demandé dans le
      cahier des charges.

--------------------------------------

Au niveau des pages catégories, elles contiennent :
    - Une navbar semblable à celle de la page d'accueil.
    - Le nom de la catégorie avec une petite phrase d'accroche en dessous en plus, afin d'inciter l'utilisateur à rester sur la page.
    - Une grille de prévisualisation, qui contient deux produits, car j'ai 8 produits en tout, dont 2 pour chaque catégorie. Cette grille
      contient le titre de chaque produit, son affiche en guise d'image de présentation, ainsi que son prix. Chaque produit est cliquable et
      envoie vers la page dédiée du produit.
    - Un footer, semblable à celui de la page d'accueil, mais avec un fond bleu marine.

--------------------------------------

Pour finir, il y a la page Support. Elle sert à me contacter via un formulaire de contact. Ce dernier est alimenté par formspree.io, un site
semblable à Web3Forms. Il se compose de deux parties


--------------------------------------

Le site complet est adapté en responsive desktop, téléphone, et tablette comme demandé, avec comme modèles de référence :
    - Desktop : Asus Vivobook S16 (mon ordinateur portable)
    - Téléphone : Iphone 16 Pro Max
    - Tablette : Ipad Pro 13

De plus, j'ai voulu ajouter des petites modifications en responsive mobile et tablette, en mettant des images spécifiquement
pour mobile ou tablette en image de fond des pages de sites web.

Aussi, en responsive, que ce soit tablette ou mobile, j'ai parfois mis un logo différent dans la navbar (c'est très souvent le cas),
pour apporter plus d'originalité à mon site.

Mon but était de faire un site agréable, interactif et sur lequel il serait plaisant de naviguer.

--------------------------------------

BONUS :

Comme bonus, j'ai créé un dépôt github, consultable grâce au lien suivant : , sur lequel au fil de la construction de mon projet, j'ai créé
des sauvegardes avec un nom qui donnait des informations sur l'état dans lequel mon site était, au moment de cette sauuvegarde.