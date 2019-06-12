# autocomplete-element
A simple Autocomplete element

## User Inputs

A user can:

* Change the active option with up/down arrow keys
* Select option by clicking with a mouse-click or pressing Return (Enter) key

### Methods Required

* `onChange`: to check options when input changes
* `onKeyDown`: to check return and arrow keys
* `value`: onChange blocks user from typing into the input field, so we have to fill the value this way

### States Required

* `showOptions`: boolean (true/false)
* `filteredOptions`: array of items that match with user input
* `activeOption`: location of currently selected item in filteredOptions, index (Number)
* `optionList` will render JSX with options (in `<ul>`) that user can choose from. The rendered JSX uses states, and is re-rendered when state is changed

## References

* [Build a React Autocomplete Component from scratch](https://blog.bitsrc.io/building-a-react-autocomplete-component-from-scratch-b78105324f4c)