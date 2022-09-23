# L'utilisation du singulier et du pluriel en ruby

Conformément à la convention de nomenclature Ruby on Rails : 

## Pour la Base de données
> Les noms de table sont au pluriel parce qu'elles contiennent plusieurs lignes de données.
> Les noms des colonnes sont au singulier.

## Pour les Modèles
> Les noms de classe de modèle sont au singulier parce qu'ils représentent une seule instance.
> Les fichiers modèles vont dans `app/models/#{Nom_modele}.rb`.

## Pour les contrôleurs
> Les noms de classe de contrôleur est au pluriel parce qu'ils contrôlent plusieurs routes.
> Les actions du contrôleur correspondent généralement aux noms de route standard définis par Rails ( index, show, new, create, edit, update, delete).
> Les fichiers du contrôleur vont dans `app/controllers/#{Nom_controleur}_controller.rb`.

## Pour les routes
> Les noms de route sont au pluriel et correspondent généralement au contrôleur.
> Les routes singulières sont un cas particulier. Cependant, ils correspondent toujours à un contrôleur pluriel par défaut !

## Pour les 
> Les noms des vues correspondent à l'action qui fait appelle à la vue.
> Les noms des vues sont au singulier.
> Les vues entrent dans `app/views/#{nom_controleur}/#{nom_action}.html.erb`.