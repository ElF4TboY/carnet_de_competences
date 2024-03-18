# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage ✔️
- les normes `ecmascript` ✔️
- l'utilisation de l'`asynchrone` ✔️
- les spécifités du mot-clef `this` ✔️

## 💻 Je code en Javascript

### Un exemple de code commenté ✔️

```
class Car {
  // permet de créer et de d'intialiser un objet
  constructor(make, model, year) {
    (this.make = make), (this.model = model), (this.year = year);
  }

  // methode accéssible depuis l'extérieur de la classe (public)
  add() {
    console.log(`La voiture ${this.make} ${this.model} est démarré`);
  }
}

// class qui hérite de la parente
class Suv extends Car {

  constructor(make, model, year, offRoad) {
    // héritage du constructor de la classe parente
    super(make, model, year);

    this.offRoad = offRoad;
  }

  toggleOffRoad() {
    if (this.offRoad) {
      console.log(
        `Le véhicule ${this.make} ${this.model} peut faire du offroad`
      );
    } else {
      console.log(
        `Le véhicule ${this.make} ${this.model} ne peut pas faire du offroad`
      );
    }
  }
}

// création de 2 instances
const newCar = new Car("Renault", "Mégane", 2014);
const newSuv = new Suv("Land Rover", "Defender", 1978, false);

// utilisations des méthodes
newCar.add();
newSuv.toggleOffRoad();
```

### Utilisation dans un projet ❌ / ✔️

[lien github](...)

Description :

### J'ai utilisé ce langage en production ❌ / ✔️

[lien du projet](...)

Description :

### J'ai utilisé ce langage en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
