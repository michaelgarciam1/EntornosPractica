# EntornosPractica parte 1 con Github

## Creamos un repositorio el cual utilizaremos de para entorno de nuestro trabajo
![image](https://user-images.githubusercontent.com/114613053/201415279-5cd74329-4986-4b57-9734-1feacfea1dfa.png)

Y así queda nuestro repositorio en github

![image](https://user-images.githubusercontent.com/114613053/201415418-b76040c3-f273-4533-9be9-54167f653384.png)

# Clonamos el repositorio
Copiamos la url del repositorio para clonarlo en nuestro entorno de desarrollo y hacemos un git clone URL,  que en este caso es

- git clone https://github.com/michaelgarciam1/EntornosPractica
![image](https://user-images.githubusercontent.com/114613053/201415770-30cfab83-5fca-4f5f-936b-120d2a63b0ec.png)

Con esto ya habriamos clonado el repositorio del github en nuestro local

# Status
Ponemos “git status” para ver el estado del repositorio y saber que está clonado.

![image](https://user-images.githubusercontent.com/114613053/201416151-a6a2be8b-5129-4c0c-b386-078e9f71fd4c.png)

# Añadir Memoria.txt

Añadimos “Memoria.txt” en el repositorio 

![image](https://user-images.githubusercontent.com/114613053/201416471-4689d563-8480-4996-ac27-1468370cf278.png)

Ahora hacemos commit.

![image](https://user-images.githubusercontent.com/114613053/201416878-82e61c8c-9712-4ed0-9d4f-5fd1f432f9c3.png)


# Queremos guardar los cambios y ponerlos en el repositorio main.

![image](https://user-images.githubusercontent.com/114613053/201416959-aece33a5-21a5-4bc6-b641-7acbfe0bdb70.png)

![image](https://user-images.githubusercontent.com/114613053/201417004-10c7fe60-bd6e-4940-a4ba-630de8823659.png)

![image](https://user-images.githubusercontent.com/114613053/201417042-90c8433b-2e93-4e74-80b0-483cfe6b3f35.png)


Después de sincronizar nuestra cuenta ahora nuestros cambios están en el repositorio main.

# Añadimos memoria2.txt 

Directamente desde github añadimos memoria2.txt

![image](https://user-images.githubusercontent.com/114613053/201417290-a2930b2d-5c39-4d5a-9e41-d7c4927a234d.png)


## Actualizamos nuestro repositorio local

En nuestro repositorio local ,a pesar de que haya habido cambios en el main, no se ha actualizado

![image](https://user-images.githubusercontent.com/114613053/201417390-4c28104f-1d05-429a-bb47-e04bc23e16a2.png)

Para añadir estos cambios en nuestro repositorio local debemos poner
- git pull origin main 

![image](https://user-images.githubusercontent.com/114613053/201417428-d03ad692-5dc2-41d5-9cfd-e1ec193b4b5a.png)

Y hacemos un dir sobre el la carpeta para ver los cambios:
![image](https://user-images.githubusercontent.com/114613053/201417473-8dd9a0d5-a708-47ae-ae8a-ae4931ab0271.png)

Donde podemos ver que se ha añadido memoria2.txt


# Comando checkout

Ahora queremos usar el comando checkout.Por ejemplo sobre Memoria.txt, teniendolo desde el main
![image](https://user-images.githubusercontent.com/114613053/201417557-7aa0d2b7-17ce-4e03-b547-d42699a4585c.png)

En nuestra rama de git hacemos cambios.


![image](https://user-images.githubusercontent.com/114613053/201417586-6ee9bccb-0c74-4344-b112-31eb155ea3a7.png)

Pero queremos deshacer nuestros cambios y ponerlo como está en el main. Por ello usamos el comando git checkout 
- git checkout memoria.txt

![image](https://user-images.githubusercontent.com/114613053/201417634-e8150cb8-032f-4e4a-8b14-0bd836daffed.png)
![image](https://user-images.githubusercontent.com/114613053/201417659-c2d0825b-8d44-4eea-b800-d830d405648b.png)

Que vuelve a nuestra versión anterior.


# Practica parte 2 con gitlab
## Creamos un repositorio el cual utilizaremos de para entorno de nuestro trabajo
![image](https://user-images.githubusercontent.com/114613053/201421279-dff3b20b-8874-4641-969b-c209a0011c40.png)

## Clonar el repositorio
Copiamos la url del repositorio para clonarlo en nuestro entorno de desarrollo y hacemos un git clone URL,  que en este caso es
- git clone https://gitlab.com/michael866/EntornosGitlab.git
![image](https://user-images.githubusercontent.com/114613053/201421542-f3ab1481-6808-4c1b-b512-ac7b3ecb1d26.png)

En este caso , a diferencia de github, nos pide identificarnos al clonar el repositorio del gitlab por primera vez

## git status
hacemos un git status para ver el estado del git
![image](https://user-images.githubusercontent.com/114613053/201421990-d79b667c-9cda-44ea-82a6-cc9174198a93.png)

## Añadir gitmemoria.txt a nuestra rama de git
usamos el git add gitmemoria.txt 
![image](https://user-images.githubusercontent.com/114613053/201422763-bae62a34-c133-4b00-b222-04b28a636117.png)

## commit
![image](https://user-images.githubusercontent.com/114613053/201423273-3bdf9fb4-f191-494f-ac1a-9fe87d9a6704.png)

## push main 
Ahora queremos guardar los cambios y ponerlos en el repositorio main.
![image](https://user-images.githubusercontent.com/114613053/201423637-bff66da3-5f5a-4aac-953a-0929119c7d0d.png)

Nuestros cambios están en el repositorio main

![image](https://user-images.githubusercontent.com/114613053/201423596-aede5e68-c8ef-4901-9b4d-2c046a8eb150.png)

## Actualizamos nuestro repositorio local

Añadimos un archivo en el repositorio main 
![image](https://user-images.githubusercontent.com/114613053/201423881-4f4b4982-1fa2-48d1-998a-4c8dfe30e0e1.png)

Nuestro repositorio local aun no se ha actualizado
![image](https://user-images.githubusercontent.com/114613053/201424109-36499e01-63ac-401b-bbf8-85de92efc1b9.png)

Para ello debemos usar el -git pull para el main
- git pull origin main 
![image](https://user-images.githubusercontent.com/114613053/201424208-88a227db-bb92-4339-b73d-4b80b81f956c.png)

Y ahora podemos ver el repositorio actualizado:

![image](https://user-images.githubusercontent.com/114613053/201424276-2d4257bd-e73b-4e13-9b93-643c4593a61e.png)






