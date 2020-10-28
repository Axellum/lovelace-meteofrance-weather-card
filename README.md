# Lovelace Météo France weather-card - Version à icones fixes

![Weather Card](https://github.com/Axellum/lovelace-meteofrance-weather-card/blob/Meteo-France/fixe-fdnoir.png?raw=true)

Adaptations de la carte https://github.com/hacf-fr/lovelace-meteofrance-weather-card:

- Remplacement des icônes (resortent mieux avec un thème sombre), possibilitée de remettre les icones d'origine.

- Différentiation des icônes sur certains arguments (notamment le brouillard).

Les icônes viennent de https://icon-icons.com/fr/pack/The-Weather-is-Nice-Today/1370, création de Laura Reen. J'ai parfois apporté de légère modifications.

Projet reprit de https://github.com/Imbuzi/meteo-france-weather-card, pour une adaptation de la carte https://github.com/bramkragten/weather-card dédié à Météo France.

![Weather Card](https://github.com/Axellum/lovelace-meteofrance-weather-card/blob/Meteo-France/carte-icone-fdbl.png?raw=true)

![Weather Card](https://github.com/Axellum/lovelace-meteofrance-weather-card/blob/Meteo-France/anime-fdblc.png?raw=true)


## Installation:

Ajoutez l'adresse https://github.com/Axellum/lovelace-meteofrance-weather-card dans "Custom repositories" sur HACS, "Category": "Lovelace".

## Configuration:

1/ Ajouter une carte manuel.

2/ Mettre:
```yaml
type: 'custom:meteofrance-weather-card'
```
3/ "Afficher l'éditeur de code" (cela affichera l'éditeur visuel)

4/ Si besoin, vous pouvez renseigner "Icones location" avec l'adresse pointant en locale les icones animées d'origine (par example):
```yaml
/local/community/lovelace-meteofrance-weather-card/icons/
```
5/ Choisir votre weather Météo France en Entity.
Cela renseignera automatique les différents sensor, il vous faudra renseigner Vigilance Météo par le sensor vigilance de votre région.

![reglages_graph](https://github.com/Axellum/lovelace-meteofrance-weather-card/blob/Meteo-France/regl-carte-icone.png?raw=true)
