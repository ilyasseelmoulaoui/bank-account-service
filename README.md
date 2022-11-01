# bank-account-service
First Micro service REST Connector

                                    Atelier 3 : Micro-Service

Travail à faire :
1. Créer un projet Spring Boot avec les dépendances Web, Spring Data JPA, H2, Lombok
2. Créer l'entité JPA Compte
3. Créer l'interface CompteRepository basée sur Spring Data
4. Tester la couche DAO
5. Créer le Web service Restfull qui permet de gérer des comptes
6. Tester le web micro-service en utilisant un client REST comme Postman
7. Générer et tester le documentation Swagger de des API Rest du Web service
8. Exposer une API Restful en utilisant Spring Data Rest en exploitant des projections
9. Créer les DTOs et Mappers
10. Créer la couche Service (métier) et du micro service








SpringBoot Application
![image](https://user-images.githubusercontent.com/4341904/199359969-45172798-0bab-4d5c-9b24-38a88446bb96.png)

Entité BankAccount
![image](https://user-images.githubusercontent.com/4341904/199360010-2efb5010-69a3-4e0f-815a-ce0b2668fca7.png)
![image](https://user-images.githubusercontent.com/4341904/199360017-33053f68-ce7f-4608-ac32-0be5d52e22e9.png)

JPA Repository
![image](https://user-images.githubusercontent.com/4341904/199360055-c9bfb5b2-c9b6-461e-aa6a-23919060aca3.png)
Si vous voulez créer une app native vous pouvez utiliser GraalVM pour rendre le temps de démarrage très court.

H2-console
![image](https://user-images.githubusercontent.com/4341904/199360108-cfa6bea3-9593-470e-90c3-55ac300d4376.png)

Controller
![image](https://user-images.githubusercontent.com/4341904/199360128-cb763938-c0f9-47a0-ba2f-0fd69045cfab.png)

Consulter tous les comptes
![image](https://user-images.githubusercontent.com/4341904/199360150-98bb6ffc-29d4-4408-bca7-04c0ffc54b02.png)

Consulter un compte
![image](https://user-images.githubusercontent.com/4341904/199360173-35c8ace3-8e1c-4846-84f7-f0461c7333f9.png)

Consulter tous les comptes
![image](https://user-images.githubusercontent.com/4341904/199360208-30714fb3-6eb1-4959-a650-31b4917a0d16.png)

Consulter un compte
![image](https://user-images.githubusercontent.com/4341904/199360247-f24534e3-760c-47f3-ab27-737f99a34883.png)

Ajouter un compte
![image](https://user-images.githubusercontent.com/4341904/199360276-bbe71e1c-993f-42bd-9a88-3b1b857f3a38.png)

Modifier un compte
![image](https://user-images.githubusercontent.com/4341904/199360307-f3085cd4-e575-4fe0-ae8c-fdefb8af66f8.png)

![image](https://user-images.githubusercontent.com/4341904/199360331-7ae92993-1c68-4629-90d0-05a5272fef30.png)

![image](https://user-images.githubusercontent.com/4341904/199360353-e11d7dd2-34e6-476e-a996-dd0dd4a8c1b2.png)

Spring data Rest
![image](https://user-images.githubusercontent.com/4341904/199360389-276d4615-2f6d-424f-b54f-3d44736e3a2b.png)

![image](https://user-images.githubusercontent.com/4341904/199360451-3a41ce8d-0997-45c5-b85f-c80630017ad8.png)

![image](https://user-images.githubusercontent.com/4341904/199360464-09f760b6-fbbf-4eab-89ca-be64f86a324a.png)

Projection
![image](https://user-images.githubusercontent.com/4341904/199360492-cc49100b-e105-4f55-afe2-c0c01d2d40e7.png)
![image](https://user-images.githubusercontent.com/4341904/199360500-36ae5fc6-bd51-463e-bd17-4329e7517878.png)

Service
![image](https://user-images.githubusercontent.com/4341904/199360527-373523fc-a2f2-4703-b079-2184b404f79a.png)

DTO Request
![image](https://user-images.githubusercontent.com/4341904/199360545-97ef8346-9016-4424-bb34-0308da84b133.png

DTO Response
![image](https://user-images.githubusercontent.com/4341904/199360562-af8a5294-7d3e-4a7a-9fa9-fa4c16b97419.png)

________________________________________________

Swagger:

consulter tous les comptes
![image](https://user-images.githubusercontent.com/4341904/199360575-838a695c-6a46-4468-8f97-4aa2493abd85.png)

consulter un compte
![image](https://user-images.githubusercontent.com/4341904/199360649-c58e7dec-54c8-41b8-97e1-b235b5a6d7c6.png)

ajouter un compte
![image](https://user-images.githubusercontent.com/4341904/199360717-3cbaae0e-52c2-4a9e-9aae-02c91ccd4787.png)
![image](https://user-images.githubusercontent.com/4341904/199360724-0a462ebc-67aa-47a0-a0d5-61ff80cd4b2e.png)

supprimer un compte
![image](https://user-images.githubusercontent.com/4341904/199360749-d7d096ba-ba90-4e2c-a45c-34b9634378ff.png)

____________________________________________

GraphQL connector :
![image](https://user-images.githubusercontent.com/4341904/199360863-b130c9e4-6fcb-4552-a37d-a9fd5d319175.png)

Dans ressources, on ajoute
![image](https://user-images.githubusercontent.com/4341904/199360921-5f88fc8a-c139-47c4-825b-b75acd0f8b67.png)

Application.properties
![image](https://user-images.githubusercontent.com/4341904/199361117-ffa3f2b0-8c7e-4273-9866-3d55c031e9f6.png)

consulter tous les comptes
![image](https://user-images.githubusercontent.com/4341904/199361157-0542f427-c062-46b0-92d4-2b84e6c36f85.png)

consulter un compte
![image](https://user-images.githubusercontent.com/4341904/199361202-cb8da76b-748c-4d01-86d4-68f063b7dc80.png)

Exception si ce compte n’existe pas.
![image](https://user-images.githubusercontent.com/4341904/199361228-18abefb3-ef27-4010-af99-327b5835f700.png)
On voit que l’exception n’est pas claire, pour cela nous allons d’ajouter a Handler d’exception

![image](https://user-images.githubusercontent.com/4341904/199361259-ecb6a337-9916-4492-af46-12f2fa2573d5.png)

Et on reçoit le résultat suivant
![image](https://user-images.githubusercontent.com/4341904/199361282-a247ba5d-6c95-426f-b64d-4e91aa7d96a4.png)

Ajouter un compte
![image](https://user-images.githubusercontent.com/4341904/199361310-71348c94-3f2b-49c4-989d-1aefb2581a95.png)

Autre méthode
![image](https://user-images.githubusercontent.com/4341904/199361323-56da5129-351c-4e5c-a19c-712a9bac8226.png)

Mettre à jour un compte 
![image](https://user-images.githubusercontent.com/4341904/199361348-15e60042-d8d2-44db-883a-709cd78a1380.png)

Supprimer un compte 
![image](https://user-images.githubusercontent.com/4341904/199361372-f3d1649a-83cb-4f66-b03c-c7ddba549bb5.png)

__________________
Les relations

Table Customer
![image](https://user-images.githubusercontent.com/4341904/199361440-670ce200-54d0-42e2-a2e3-e7fc7b3ddf08.png)

Table BankAccount
![image](https://user-images.githubusercontent.com/4341904/199361456-d9ff93e5-ac55-41c6-8d0b-4eb161be94d3.png)

![image](https://user-images.githubusercontent.com/4341904/199361475-5bed4740-3e6e-4352-9c49-7420a5e415c7.png)

Consulter tous les clients
![image](https://user-images.githubusercontent.com/4341904/199361502-9f36aec9-7fa1-482a-8563-19a2d14597ec.png)





