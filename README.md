this project is for understanding styling in React Projects better.
As until now we were writing CSS in global namespace

we have -
- conditional and dynamic styling
- styled components
- CSS modules


the way we were adding CSS till now, every CSS was working on all components globally, we don't want
that, so for this -

1. styled components (npm package)
it helps us in creating styles, which are only attached to a specific component. Hence will affect only
that component, and not any other component.

2. CSS Modules
project needs to have configuration made to support it. All the projects made by create-react-app has
these configurations already done for them.
