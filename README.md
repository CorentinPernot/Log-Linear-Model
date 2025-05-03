# Log-Linear Model

Projet de 2ᵉ année à l'ENSAE Paris, réalisé dans le cadre du cours de **Simulations and Monte Carlo**.

Les modèles log-linéaires s'appliquent à un vecteur aléatoire X ∈ {0,1}^d.  
La probabilité d'observer une certaine réalisation x est donnée, dans le cas d’un modèle restreint aux interactions d’ordre 2, par :

**log P(X = x) = α + Σ βᵢ xᵢ + Σ γᵢⱼ xᵢ xⱼ**,  
où les sommes sont respectivement sur i = 1,…,n et i < j.

## Contenu du projet

- **Question 1** : génération de données à partir de paramètres fixés β et γ.
- **Questions suivantes** : inférence des paramètres à partir d’une distribution donnée.

## Auteurs

Charles Rollet, Alexandre Partensky et Corentin Pernot

## Sources

- *Cours de Monte Carlo*, Nicolas Chopin  
- *MCMC for doubly-intractable distributions*, I. Murray, Z. Ghahramani, D. J. C. MacKay  
  https://mlg.eng.cam.ac.uk/zoubin/papers/doubly_intractable.pdf  
- *Computational Statistics*, T. Denœux  
  https://www.hds.utc.fr/~tdenoeux/dokuwiki/_media/en/mcmc_slides.pdf
