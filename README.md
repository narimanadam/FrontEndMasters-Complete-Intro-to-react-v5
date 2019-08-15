# Complete Intro to react - v5
### Create React Component from Scratch
```js
const App = () => {
    return react.createElement(
        "div",
        {},
        React.createElement("h1", {}, "Adopt Me!")
    )
}

ReactDOM.render(React.createElement(App), // component tag name
    document.getElementById("root")) // where to render the component
```

