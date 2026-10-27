# IronPath Gallery 💪

Exercise images and data used by **[IronPath](https://henriqueinfdev.github.io/IronPath-Web/)**, a workout tracker for Android by **Henrcxs Studio**.

The app loads the pictures in [`exercises/`](exercises) to show how each exercise is done. They are cached on the device, so after being seen once they also work offline.

## Structure

```
exercises/
  <Exercise_Id>.json      exercise data (name, muscles, equipment, level, instructions)
  <Exercise_Id>/0.jpg     start position
  <Exercise_Id>/1.jpg     end position
```

Each JSON file follows [`schema.json`](schema.json).

## Credits

This gallery is a copy of **[free-exercise-db](https://github.com/yuhonas/free-exercise-db)**, created by **[Clint Plummer (yuhonas)](https://github.com/yuhonas)** with contributions from [Benjamin Stürmer (thebino)](https://github.com/thebino), [ZerGo0](https://github.com/ZerGo0) and [Josh Tucker (jtucker2)](https://github.com/jtucker2). The original project builds on [exercises.json](https://github.com/wrkout/exercises.json).

Many thanks to them for making this data freely available. The full history of the original project is kept in this repository.

## License

Public domain, under [The Unlicense](LICENSE.md), the same license as the original project. You are free to use, copy and modify it.

---

### Português

Imagens e dados dos exercícios usados pelo app **IronPath** (Henrcxs Studio). É uma cópia do projeto aberto **[free-exercise-db](https://github.com/yuhonas/free-exercise-db)**, criado por **Clint Plummer (yuhonas)** e colaboradores, a quem agradecemos. Domínio público ([Unlicense](LICENSE.md)).
