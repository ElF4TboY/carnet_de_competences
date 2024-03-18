# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
- les types de bases ✔️
- comment et pourquoi étendre une interface ✔️
- les classes et les decorators ✔️

## 💻 J'utilise

### Un exemple personnel commenté ❌ / ✔️

```
class Car {
  // typage des variable
  make: string;
  model: string;
  year: number;

  // permet de créer et de d'intialiser un objet
  constructor(make: string, model: string, year: number) {
    (this.make = make), (this.model = model), (this.year = year);
  }

  // methode accéssible depuis l'extérieur de la classe (public)
  add() {
    console.log(`La voiture ${this.make} ${this.model} est démarré`);
  }
}

// class qui hérite de la parente
class Suv extends Car {
  offRoad: boolean;

  constructor(make: string, model: string, year: number, offRoad: boolean) {
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

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

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
