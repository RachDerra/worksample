# Qu'est-ce que Self
Self est un mot-clé Ruby qui vous donne accès à l'objet courant.
Cet « objet courant » dépend du contexte (le contexte est l'endroit où se trouve votre code à un moment donné).
Donc, si vous êtes dans une instance, self fait référence à l'instance. Si vous êtes dans une classe, self fait référence à cette classe.
Ruby utilise self partout : Pour les variables d'instance, lors de la définition des méthodes, des classes et des modules.
# Comment utiliser Self
* Utilisation de Self pour la désambiguïsation

```
class Foo
  def self.bar
    "methode de classe bar"
  end

  def bar
    "instance de la methode bar"
  end
end

Foo.bar  => "methode de classe bar"

foo = Foo.new
foo.bar => "instance de la methode bar"

```

Dans ce exemple, Self est utilisé pour montrer la différence entre "Une méthode de classe" et "Une instance de la classe".