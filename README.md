# CSS Trivias

Trivia games developed using HTML and CSS, without JavaScript or any other scripting language.

## How they work

To simulate the click event, two different techniques are used:

- **`label` + `input`**: using a `label` with a non-visible checkbox/radio allows to create a two-state switch.
- **`a` + `:target`**: the `:target` selector allows to define styles for the currently active element (as specified by the URL fragment, aka the hash in the url), the links will change the current anchor.

Moving the checkbox/radio buttons to the root allows for more flexibility as we can use the general sibling combinator (`~`) to "move" from one question to another.

## Demo

You can see the trivia games running on Codepen:

- [Trivia-1](https://codepen.io/alvaromontoro/pen/jGLOBy)
- [Trivia-2](https://codepen.io/alvaromontoro/pen/aLLbvV)
