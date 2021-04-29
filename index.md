# react-native-help-create

This command line helps you create components, screens and even redux implementaion for your react native project.

# Functionalities

- Delete entire folder that combines screens or components.
- Delete multiple screens and components.
- Create multiple screens and components to a specific folder if needed.
- Combine components and screens in a specified folder.
- Support for TypeScript and JavaScript.
- Create components and check if already exists.
- Create screens and check if already exists.
- Create redux implementation and check if already exists.
- Delete components after checking if exists.
- Delete screens after checking if exists.
- Delete redux implemnetation after checking if exists.

# How to install it?

To install it you should type on your shell the following

```
npm i react-native-help-create -g
```

in order to install it globally in your system.

# How to use it?
## Table of Contents

1. [Summary](#summary)
2. [`rnhc create`](#rnhc-create)
3. [`rnhc delete`](#rnhc-delete)
4. [`rnhc combine`](#rnhc-combine)
5. [Notes](#notes)

### Summary

- You can run this `rnhc --help` to see the available commands.
- By default `rnhc` helps you create components, screens and redux implementation in JavaScript (so `--js` is optional).
- If you want to create in TypeScript you just need to add the option `--ts`.
- You don't need to specify the language option in `delete` mode nor in `combine` mode.

Here are the following commands and how to use them

---

### `rnhc create`

- Runc `rnhc create --help` to see the available options.

- To create a component run

```
rnhc create -c <component_name>
```

- to create a screen run

```
rnhc create -s <screen_name>
```

- to create a redux implementation run

```
rnhc create -r <redux_name>
```

- to create multiple components run

```
rnhc create -c <component_name_1> <component_name_2> ...
```

- to create multiple screens run

```
rnhc create -s <screen_name_1> <screen_name_2> ...
```

- to create a component or multiple components in a specific folder run

```
rnhc create -c <component_name_1> <component_name_2> ... -f <folder_name>
```

- to create a screen or multiple screens in a specific folder run

```
rnhc create -s <screen_name_1> <screen_name_2> ... -f <folder_name>
```

---

### `rnhc delete`

- Run `rnhc delete --help` to see the available options.

- to delete a component run

```
rnhc delete -c <component_name>
```

- to delete a screen run

```
rnhc delete -s <screen_name>
```

- to delete a redux implementation run

```
rnhc delete -r <redux_name>
```

- to delete multiple components run

```
rnhc delete -c <component_name_1> <component_name_2> ...
```

- to delete multiple screens run

```
rnhc delete -s <screen_name_1> <screen_name_2> ...
```

- to delete an entire folder that combines components run

```
rnhc delete -c -f <folder_name>
```

- to delete an entire folder that combines screens run

```
rnhc delete -s -f <folder_name>
```

---

### `rnhc combine`

- Run `rnhc combine --help` to see the available options.

- to combine specific components in a folder run

```
rnhc combine -c <component_name_1> <component_name_2> ... -f <folder_name>
```

- to combine specific screens in a folder run

```
rnhc combine -s <screen_name_1> <screen_name_2> ... -f <folder_name>
```

---

### Notes

- Keep in mind that you are at the root of your react native project, the command will check eaither way.

- `rnhc` will always check if files or folders are existed for all commands.

# Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
