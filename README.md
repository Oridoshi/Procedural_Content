# TP6 GODOT — Monde procédural avec Compute Shader

## Auteurs
- [Tom DUNET](https://github.com/Oridoshi) (DUNT18030400)  
- [Martin QUEVAL](https://github.com/MartinQueval) (QUEM25040400)  

## Objectif
Le but de cette partie est d’optimiser la génération d’un monde procédural grâce à un `compute shader`.  
Pour cela, vous devez remplir le fichier suivant dans le projet Godot C# :

```
Shaders/heightmap_compute.glsl
```

Votre tâche est d’implémenter la fonction `main()` afin de générer une heightmap, qui sera utilisée plus tard pour construire dynamiquement un monde 3D.

---

## Détails du projet

Le projet utilise le moteur **Godot** en version C# (pensez à installer cette version pour ouvrir le projet correctement).  
Le shader doit être optimisé pour fonctionner efficacement sur différentes résolutions d’images.  
La heightmap sera utilisée pour déterminer la topographie du monde, à partir d’un bruit procédural.

---

## Extension utilisée

Ce projet utilise également l’extension **ImGui pour Godot** :  
[https://github.com/pkdawson/imgui-godot](https://github.com/pkdawson/imgui-godot)

> ⚠️ Pensez à consulter le README officiel pour l'installation et la configuration.  
> En principe, le projet est déjà configuré, mais en cas de problème, référez-vous à la documentation fournie.

---

## Rappel

- Forkez ce dépôt :  
  [https://github.com/VALERE91/Procedural_Content](https://github.com/VALERE91/Procedural_Content)

- Implémentez la logique dans `heightmap_compute.glsl` pour générer une heightmap procédurale cohérente.

- Testez la génération dans Godot via le système de rendu prévu.

---

Bonne génération de monde ! 🚀

