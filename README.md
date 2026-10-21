# task-management

An Expo app that is still the stock template, with no task features yet.

**Status:** Stub. The app has only two source files, and the only screen is the default `create-expo-app` placeholder ("Edit app/index.tsx to edit this screen.").

## The problem

The repo name suggests a task manager, but the code does not yet show one. The project was created from the Expo starter and has not been changed.

## What it does

Nothing yet. The root screen in `app/index.tsx` renders a centred placeholder text.

## How it's built

- Expo with file-based routing through `expo-router`: screens live under `app/`, and the directory layout defines the routes.
- React Native, TypeScript, and `react-native-reanimated` and `react-native-gesture-handler` are listed as dependencies.

## Running it locally

```bash
npm install
npm start
```

`npm start` runs `expo start`. The package also defines `android`, `ios`, `web` and `lint` scripts.

## What's left

- No task features: no data model, storage, or task screens.
- The screen is the Expo placeholder.
- No tests. `react-test-renderer` is a dev dependency, but there are no test files.
