pwd
mkdir ejercicios
cd ejercicios/
code
mkdir ejercicios1

git config --global user.name "Andres Zuluaga"
git config --global user.email "afzuluag@gmail.com"
git init
git add .
git commit -m "Version Inicial"
git add README.md
git commit -m "Agregar solucion primer ejercicio"
git remote add origin https://github.com/afzuluag/aspirantes-mir-ejercicio-1.git
git push origin master