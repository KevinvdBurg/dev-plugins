# Expo DevTools Plugins

- A collection of Expo DevTools Plugins.

## Awesome Plugins

- `@dev-plugins/react-query`: Plugin for [TanStack Query](https://tanstack.com/query/latest/)

  - Credit: Most code are forked from [react-query-native-devtools](https://github.com/bgaleotti/react-query-native-devtools)

- `@dev-plugins/react-navigation`: Plugin for [React Navigation](https://reactnavigation.org/)

  - Credit: Most code are forked from [@react-navigation/devtools](https://github.com/react-navigation/react-navigation/tree/4797ace/packages/devtools) and the [Flipper plugin frontend](https://github.com/react-navigation/react-navigation/tree/4797ace/packages/flipper-plugin-react-navigation)

## Example App

The [example app](/apps/example) is an [Expo Router](https://docs.expo.dev/routing/introduction/) app that provides test cases for plugins

- Expo Router is based on React Navigation, so you can just test `@dev-plugins/react-navigation` from visiting different screens from the app.
- [`React Query`](/apps/example/src/app/react-query/): React Query example forked from https://github.com/TanStack/query/tree/5b9be1e299257e32c4c294796711f5d82f968530/examples/react/react-native
- [`React Query Time`](/apps/example/src/app/react-query-time/): React Query example forked from https://github.com/bgaleotti/react-query-native-devtools/tree/799efff17b08e9793ab27d5a93457c5d5510233c/apps/Time
