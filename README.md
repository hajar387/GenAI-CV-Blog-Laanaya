# GenAI-CV-Blog-Laanaya

## 1.C’est quoi le Generative AI en CV ?

Le Generative AI en Computer Vision est une technologie qui permet à une machine de créer de nouvelles images à partir de données existantes.
Contrairement aus modéles classiques comme CNN qui analysent les images , Le Generative AI génere du contenu visuel

### Idée simple :
On peut imaginer la machine comme un artiste :

elle append à partir de plusieurs images 

puis elle crée une nouvelle image similaire 

<img width="1682" height="515" alt="image" src="https://github.com/user-attachments/assets/f4e1ff8f-c39d-47da-b860-3821cc1b87a2" />

### Exemples concrets :
Générer un visage humain qui n'existe pas 

Transformer un dessin simple en image réaliste 

Créer une image à partir d'un texte 

## 2.Pourquoi utiliser GenAI ?

Le Generative AI est utilisé pour plusieurs raisons importantes :

#### Création de contenu :
Génération d'images , avatars , logos et aide au design , ...

#### Augmentation de données : 
Générer de nouvelles images  pour entrainer les modeles . 
Par exemple : créer des images médicales pour améliorer un modeles .

#### Application dans les industries :
Jeux vidéo (création de personnages ) ,cinéma (effets spéciaux) , ...

#### E-commerce et marketing :
Essayage virtuel , Génération d'images de produits , ...

#### Céativité assistée :
Aider les designers , générer rapidement des idées visuelles , ...

## 3.Les architectures principales (ELI5) et la difference entre eux :

Il existe 3 grandes méthodes en Generative AI pour créer des images :

GAN (Generative Adversarial Network)

VAE (Variational AutoEndoder)

Diffusion Models 

Chaque modele a une facon différente de générer des images .

### GAN (Generative Adversarial Network) :

Le GAN contient 2 réseaux de neurones qui s'entrainent en meme temps :

#### 1.Generatore ( le créateur ) : Il prend du bruit aléatoire . puis il essaie de créer une image réaliste . Au début , ses images sont mauvaises .

#### 2.Discriminator ( le juge ) : Il recoit des vraies images et des images générées , et il doit dire : vrai ou faut .

#### Comment ils aaprennent ?

C'est un jeu d'amélioration continue :

1. Generator crée une image
2. Discriminator dit c'est faux
3. Generator aprend de ses erreurs
4. Generator devient meilleur
5. Discriminator devient aussi meilleur

=> Dans le résultat on a une compétition permanante

<img width="1310" height="649" alt="image" src="https://github.com/user-attachments/assets/8f2a3d40-a7ba-4de9-9e05-1f706c2075f2" />


#### Analogie :

Comme un faux-monnayeur et un policier : 

- le faux-monnayeur fabrique de faux bilets
- le policier essaie de la détecter

Avec le temps : 
Le faussaire essaie de tromper le policier , et le policier devient de plus en plus intelligent ,

- Résulat : les faux billets deviennent tres réalistes

### VAE (Variational AutoEndoder) :

Le VAE fonctionne avec 2 parties principales : 

#### 1.Encoder : Prend une image , et la transforme en représentation compressée ( latent space ) comme un résumé 

#### 2.Decoder : Prend ce résumé et reconstruit une image 

=> Contrairement à GAN : VAE ne copie pas directement , il apprend une distribution de données .

<img width="1556" height="590" alt="image" src="https://github.com/user-attachments/assets/320286b8-fd16-43ac-94c7-027ccb6891cd" />


#### latent space :

C'est un espace magique ou : chaque image est un point , les images similaires sont proches .

Par exemple : Visages souriants proches des visages sourients , visages  tristes proches des visages tristes 

<img width="1395" height="630" alt="image" src="https://github.com/user-attachments/assets/18225463-19aa-4421-afce-6e79788b8de3" />


#### Analogie : 
Comme un résumé + réécriture : 

-lire un livre 
-faire  un résumé 
-réécrire une version dasée sur ce résumé 





