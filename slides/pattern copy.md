## Patterns DevOps

----

### Collaboration entre Devs et Ops

<img src="https://web.devopstopologies.com/images/type-1.png" width="50%" />

* Saint Graal du DevOps
* Travaillent sur des produits séparés
* Les Ops doivent être à l'aise sur Git et les Devs sur les problématiques de production

----

### Responsabilité Ops partagées

<img src="https://web.devopstopologies.com/images/type-2.png" width="50%" />

* Peu de séparation entre Devs et Ops
* Intégration des Ops dans l'équipe de Devs
* Travaillent sur des produits

----

### Ops comme Infrastructure-as-a-Service

<img src="https://web.devopstopologies.com/images/type-3.png" width="50%" />

* Généralement lors de l'utilisation de cloud
* Suit les pratiques TDD, CI, développement itératif, etc.
* Toujours une équipe de Devs

----

### DevOps en tant que service externe

<img src="https://web.devopstopologies.com/images/type-4.png" width="50%" />

* Peut être appelé aussi DevOps-as-a-Service
* Les Devs se basent sur des services externes type AWS, Azure, GCP, ...
* Généralement pour des petites équipes

----

### Equipe DevOps temporaire

<img src="https://web.devopstopologies.com/images/type-5.png" width="50%" />

* Interface entre Devs et Ops
* A une durée de vie limitée contraintement à l'anti-pattern B (Silo équipe DevOps)
* Son rôle est de faire évoluer les pratiques d'entreprise

----

### Equipe DevOps Advocate

<img src="https://web.devopstopologies.com/images/type-6.png" width="50%" />

* Aide à diffuser les pratiques DevOps
* Généralement efficace lorsque le gap à combler est grand
* Parle le langage des Devs et des Ops

----

### Modèle SRE

<img src="https://web.devopstopologies.com/images/type-7.png" width="50%" />

* Modèle Google
* Automatise le déploiement à outrance
* Peut refuser les livraisons si le code est de mauvaise qualité

----

### Collaboration par containers

<img src="https://web.devopstopologies.com/images/type-8.png" width="50%" />

* Le container est l'artifact de livraison universel
* Ne marche plus si les Devs ignorent les contraintes de production
