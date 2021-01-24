# Pokedex using Redux

The target is to build a self-contained web application in React & Redux, using the rest API from https://pokeapi.co/ with the following features:  
- Display a list with all the Pokémon
- Filter the list of the Pokémon by name or Pokémon number
- Be able to see the details of any Pokémon (description, stats, etc.)
- Add a Pokémon to “My Pokémon” list
- Remove a Pokémon from “My Pokémon” list
- View the “My Pokémon” list
- View details of any entry in “My Pokémon” list
- The “My Pokémon” should be persistent across page reloads

## Mention Dependencies

- Redux for handling Application State management
- redux-persist and redux-thunk to work with redux store and do it persistent.
- react-lazyload from [https://github.com/twobin/react-lazyload](twobin/react-lazyload) to lazyload all the images in a list.
