# Hello World with CDNs

There are 2 approaches to this. One with JSX via babel and another one in pure JavaScript.

## Without JSX

```html
<html>
<head>
    <script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
</head>
<body>
    <div id="react-container"></div>
    <script>
        const App = React.createElement('h1',
        { 
            id: 'title',
        },
        'Hello World!');
        ReactDOM.render(
            App, document.getElementById('react-container'))
    </script>
</body>
</html>
```
[Click here for demo](/examples/react-cdn.html)

## With JSX

```html
<html>
<head>
    <script crossorigin src="https://unpkg.com/react@16/umd/react.development.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@16/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
</head>
<body>
    <div id="react-container"></div>
    <script type="text/babel">
        const App = () => <h1 id="title" >Hello World!</h1>
        ReactDOM.render(
            <App />, document.getElementById('react-container'))
    </script>
</body>
</html>
```
[Click here for demo](/examples/react-cdn-jsx.html)