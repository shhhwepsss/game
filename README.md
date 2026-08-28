# game

Хобби-проект на Unity.

## Требования

- **Unity 6000.0.82f1** (Unity 6 LTS) — ставится через Unity Hub
- Модули: Web Build Support, Windows Build Support (IL2CPP)
- [Git LFS](https://git-lfs.com/) — бинарные ассеты (текстуры, модели, звук) лежат в LFS

## Как запустить

```bash
git clone https://github.com/shhhwepsss/game.git
cd game
git lfs pull
```

Дальше: Unity Hub → *Add project from disk* → выбрать папку `game` → открыть.

Стартовая сцена — `Assets/Scenes/SampleScene.unity`.

## Стек

- Render pipeline: **URP** (Universal Render Pipeline)
- Ввод: **Input System** (`Assets/InputSystem_Actions.inputactions`)
- Настройки качества/рендера: `Assets/Settings/`
