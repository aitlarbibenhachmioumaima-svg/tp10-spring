# 🛡️ TP 10 : Formulaire de connexion personnalisé

## Objectif du Tp

---

   -Décrire le flux complet d’authentification dans Spring Security.
   
   -Configurer un formulaire de login personnalisé.
   
   -Gérer les redirections après succès ou échec.
   
   -Comprendre le rôle de chaque composant (HttpSecurity, UserDetailsService, SecurityFilterChain).
   
   -Implémenter une page de logout propre.

---

## 🛠️ Structure du Projet

<img width="308" height="398" alt="image" src="https://github.com/user-attachments/assets/f099a86d-f374-464f-a6e4-6e6b794ae39a" />


## Démarrage et Lancement de l'Application

 ### Page de Connexion (Login) :
 
<img width="959" height="473" alt="image" src="https://github.com/user-attachments/assets/bcb2ba9a-bca9-4421-881d-14de7e367446" />


### Connexion en tant qu'Administrateur (ADMIN) :
 

 <img width="1919" height="946" alt="Capture d&#39;écran 2026-03-24 201318" src="https://github.com/user-attachments/assets/4133f3d4-7724-4cfa-8797-2fd5f487c1be" />

 Après validation, l'admnistrateur est redirigé vers la page d'accueil (/home).

 <img width="1919" height="947" alt="Capture d&#39;écran 2026-03-24 201406" src="https://github.com/user-attachments/assets/74d1e15b-9a08-4a85-b976-114648dd5364" />

Accès réussi à l'Espace Utilisateur :

<img width="1919" height="947" alt="Capture d&#39;écran 2026-03-24 201435" src="https://github.com/user-attachments/assets/286c3fc0-4e3e-4c3c-9980-d9e1e45f22c1" />

Accès réussi à l'Espace Admnistrateur :

<img width="1919" height="950" alt="Capture d&#39;écran 2026-03-24 201507" src="https://github.com/user-attachments/assets/918aa4a3-1484-4e08-aa3a-ebc1e877870e" />

### Déconnexion Sécurisée (Logout) :

<img width="1919" height="946" alt="Capture d&#39;écran 2026-03-24 202032" src="https://github.com/user-attachments/assets/700ee4cc-bf94-4ef4-a7a3-b8ccbb14f061" />



### Connexion en tant qu'Utilisateur (USER) :

<img width="1916" height="949" alt="Capture d&#39;écran 2026-03-24 202223" src="https://github.com/user-attachments/assets/c70b654e-f3d6-410e-96d6-5965e9611d0c" />

Après validation, l'utilisateur est redirigé vers la page d'accueil (/home).



<img width="1919" height="947" alt="Capture d&#39;écran 2026-03-24 202312" src="https://github.com/user-attachments/assets/b95ec867-12d6-486b-9151-92e7d488e41b" />


Accès réussi à l'Espace Utilisateur :

<img width="1919" height="952" alt="Capture d&#39;écran 2026-03-24 202334" src="https://github.com/user-attachments/assets/2b277e9c-3759-4eeb-9119-37bff44c4da4" />

### Déconnexion Sécurisée (Logout) :


<img width="1917" height="950" alt="Capture d&#39;écran 2026-03-24 202502" src="https://github.com/user-attachments/assets/fbf00392-67ae-4b08-a9f2-a5a724e57596" />


