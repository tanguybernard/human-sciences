# Organisation des équipes (Team design)

Notes sur les questions d'orga qui reviennent souvent : on coupe l'équipe ? on fusionne ? qui fait les petits sujets ? un nouveau dev est opérationnel quand ?

## A lire

- **Team Topologies** — Matthew Skelton & Manuel Pais. Le plus direct sur « comment découper les équipes ».


## Concepts clés

- **Charge cognitive** (Team Topologies) : une équipe doit pouvoir comprendre et porter entièrement son périmètre. C'est le premier critère pour découper.
- **Loi de Conway** : l'organisation des équipes se retrouve dans l'architecture du code (et inversement). Couper l'orga là où le système n'est pas coupé = négociation permanente.
- **Modes d'interaction** (Team Topologies) : la collaboration étroite entre deux équipes doit être **temporaire** (exploration), pas l'état normal. Si elle devient permanente, la frontière est au mauvais endroit.
- **Coût de communication** : n(n−1)/2 canaux. 6 personnes = 15 liens, 10 personnes = 45.
- **Two-pizza team** (Amazon / Jeff Bezos) : une équipe qu'on peut nourrir avec deux (grandes) pizzas américaines, donc ~6 à 10 personnes. Une image, pas une norme.
- **Loi de Brooks** : ajouter du monde à un projet en retard le retarde encore plus à court terme.

## Les questions qui reviennent

### Séparer l'équipe en 2 sur 2 gros sujets ?

- Oui **si** les deux sujets sont vraiment peu liés, dans le métier **et** dans le code.
- Sinon : « si vous devez vous coordonner tout le temps, vous aurez juste déplacé le problème dans des réunions de synchro ».
- Attention aux profils partagés (ex. une designeuse pour deux équipes) : risque de goulot d'étranglement.

### Qui fait les petits sujets ?

- Éviter l'**« équipe des restes »**.
- Découper par **périmètre métier**, pas par taille de sujet : chaque équipe prend les petits sujets de son domaine.
- Ce qui ne rentre nulle part : **rotation** (une personne de permanence par sprint).

### Pourquoi ne pas fusionner 2 équipes ?

- Au-delà de ~8–9 personnes : rituels plus lourds, l'équipe finit par se recouper toute seule de façon informelle.
- Fusionner a du sens quand deux équipes dépendent tellement l'une de l'autre qu'elles n'avancent jamais séparément.

### Un dev en plus, opérationnel quand ?

Ordres de grandeur (retours d'expérience, pas une loi) :

- Première contribution : quelques jours si l'onboarding est bon.
- Autonome sur des sujets courants : 1 à 3 mois.
- Pleinement efficace sur un domaine métier riche : plutôt 3 à 6 mois.
- Au début il **coûte** du temps à l'équipe (formation, relecture) → Brooks.

