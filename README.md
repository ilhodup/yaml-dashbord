# yaml-dashbord
Yaml comple de la carte elements image de "Home Assistant".
Ce n'est pas du copier-coller pour que ça fonctionne
car ce sont mes images et mes sensors dans le code yaml.
Mais vous pouvez utiliser des bout de codes en mettant vos image et sensors
pour faire votre dashbord animé.

Voici quelques conseilles:

- Redimensionner les images en reduisant la taille en fonction de ce que vous voulez afficher,
  un icon ne fait que quelques octets, donc eviter de mettre des images de 1Mo ou 2 Mo.
- Si vous voulez animer une image qui se déplace tout en superposant l'arriere plan,
  il faut que cette image soit en format PGN avec fond transparent. En fait l'image est
  decoupée et tout le fond est transparent de tel sorte que cette image apparesse
  en superposition.
- Il vaut mieux mettre tout ce qui est statique en image de fond pour eviter de surcharger
  le dashbord, surtout s'il y a beaucoups de conditions ou d'animations dans le dashbord.
- Copiez de la ligne 1960 à 2234 directement dans le yaml de la carte "elements image".
  Puis copier un bout de code comme par exemple telecommande Nice en changent l'image
  pour essais.
