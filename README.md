# Gestion des Salles

TP Hibernate/JPA avec base de données H2 en mémoire.

## Technologies
- Java 11 | Hibernate 5.6.5 | JPA 2.2 | H2 | Maven

## Structure
```
src/main/java/com/example/
├── model/        → Salle.java, Utilisateur.java
├── service/      → CrudService, AbstractCrudService, SalleServiceImpl, UtilisateurServiceImpl
└── App.java      → Tests CRUD
```

## Lancer le projet
Dans IntelliJ : clic droit sur `App.java` → **Run 'App.main()'**

## Résultat
```
Process finished with exit code 0
```
✅ Toutes les opérations CRUD (Create, Read, Update, Delete) exécutées avec succès sur les entités **Salle** et **Utilisateur**.

## Captures d'écran 

-- Génération automatique du schéma (hbm2ddl)

<img width="948" height="676" alt="image" src="https://github.com/user-attachments/assets/a049d19e-33d3-435d-bebe-fa42daec57a3" />

<img width="943" height="644" alt="image" src="https://github.com/user-attachments/assets/a48e891b-581e-4c76-952c-ffdff9696e4d" />

-- Création de salles

<img width="941" height="641" alt="image" src="https://github.com/user-attachments/assets/4d1a6647-c12c-4f4e-bc56-ada6af5a91f0" />

<img width="838" height="256" alt="image" src="https://github.com/user-attachments/assets/213cf49e-caa5-4539-9bcc-8d9fee7349e3" />

-- Lecture de toutes les salles

<img width="1600" height="561" alt="image" src="https://github.com/user-attachments/assets/20f53695-5e56-469a-9ebe-b483f631599f" />

-- Recherche d'une salle par ID

<img width="1600" height="556" alt="image" src="https://github.com/user-attachments/assets/2551fa8e-f547-4f66-b0a1-c5979ee6a81b" />

-- Recherche des salles disponibles

<img width="1600" height="591" alt="image" src="https://github.com/user-attachments/assets/c3269560-468a-4131-848e-b0e011a2d995" />

-- Recherche des salles avec capacité minimum de 100

<img width="1600" height="626" alt="image" src="https://github.com/user-attachments/assets/5b2f303d-54e2-46e3-a46d-107fa9889f92" />

-- Mise à jour d'une salle

<img width="936" height="509" alt="image" src="https://github.com/user-attachments/assets/d0682b96-5688-4406-aa3e-1f2db162e50f" />

![WhatsApp Image 2026-02-18 at 23 21 14](https://github.com/user-attachments/assets/e4d80784-9090-4f83-a926-ddaf2cb36478)

-- Suppression d'une salle

<img width="874" height="399" alt="image" src="https://github.com/user-attachments/assets/d3c41259-f50f-4788-86f6-3514c81dcbcc" />

<img width="949" height="756" alt="image" src="https://github.com/user-attachments/assets/bcf6ec6f-3e42-4951-b27f-ac4a54522d13" />

-- Liste des salles après suppression

<img width="1600" height="690" alt="image" src="https://github.com/user-attachments/assets/d1598c9c-b93f-465d-a9bb-46d05d8029be" />

-- Fermeture de la SessionFactory

<img width="1105" height="420" alt="image" src="https://github.com/user-attachments/assets/a1813206-9038-4940-8ffe-8064f82a4bfe" />














