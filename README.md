# Ray Tracer

Ceci est un implementation du livre Ray Tracing in One Weekend écrit par Peter Shirley qui présente les concepts fondamentaux du lancer de rayons,\
pour générer des images réalistes par ordinateur. Il couvre des sujets tels que les intersections rayons-objets, les matériaux, l'éclairage et le rendu, \
en passant progressivement à des fonctionnalités plus avancées telles que les ombres, les réflexions et les réfractions.

J'ai choisi de présenter cette réalisation du ray tracer "open" au publiques en raison de la confidentialité du code que j'ai utilisé lors de mes études qui allaient \
plus loin dans les techniques du ray tracing et path tracing. Ceci n'est en aucun cas un acte de plagiat mais pour montrer ma compréhension du lancer de rayons.
 
### Exécution
le code est écrit en C++ et peut donc être exécuté par n'importe quel compilateur prenant en charge C++.\
Le fichier étant écrit dans le flux de sortie standard, vous devrez le rediriger vers un fichier image. Le programme doit donc être construit avec cmake.\

Sous Windows, pour obtenir la version de débogage de CMake, il faut exécuter cette commande :

*cmake -B build* \
*cmake --build build* \

Ensuite, exécutez le programme comme ceci : \
*build\Debug\main.exe > image_name.ppm* \

Cette version contient déjà le fichier le fichier CMakeLists.txt avec l'ensemble d'instructions pour l'exécutable.

### Résultat
![image](https://github.com/turfa00/Ray_Tracer/assets/80334127/0205ad9e-3958-4608-904a-9193d29c3681)

### Références
Ray Tracing in One Weekend par Peter Shirley \
https://raytracing.github.io/books/RayTracingInOneWeekend.html
