# Character Roll Call - with map

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a>

> This is part of Academy's [technical curriculum for **The Mark**](https://github.com/WeAreAcademy/curriculum-mark). All parts of that curriculum, including this project, are licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>.

This project builds on the following two prior projects:

- [Roll Call](https://github.com/WeAreAcademy/mark-react-proj--roll-call)
- [Using map](https://github.com/WeAreAcademy/mark-react-basics-proj--using-map.git)

This repo doesn't need to be cloned - it's an extension to your previous Roll Call repo.

## Learning outcomes

- Refactor a component to use `.map`

## Refactoring

> 🎯 **Success criterion:** You have refactored your `App` component to use `.map`

At the end of the _Roll Call_ exercise, the `App` component is rendering 8 instances of the `Character` component.

We can make the code cleaner by using a `.map`:

1. Extract out the data from the props into an array of objects (ideally, typed using a common `interface`)
2. `.map` over the data to return the `Character` component for each element
