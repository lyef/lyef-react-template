# <%= appNameHumanized %>
[![Build Status](https://travis-ci.org/<%= authorName %>/<%= appName %>.svg?branch=master)](https://travis-ci.org/<%= authorName %>/<%= appName %>)
![Badge size](https://badge-size.herokuapp.com/<%= authorName %>/<%= appName %>/master/dist/Main.min.js.svg)
![Badge gzip size](https://badge-size.herokuapp.com/<%= authorName %>/<%= appName %>/master/dist/Main.min.js.svg?compression=gzip)

## Demo

[Live examples](https://<%= authorName %>.github.io/<%= appName %>)

## Installation

```sh
$ npm install --save <%= appName %>
```

*Remember to import the styles on `css/main.css` folder to your project.*

## Basic Usage

```jsx
import <%= appNameCamel %> from '<%= appName %>';

...
render() {
    return (
        <<%=appNameCamel %> />
    );
}
...
```

## Props

- `prop` (type) - description
- `prop` (type) - description
- `prop` (type) - description

## Architecture

We've developed this component using the following boilerplate:
[lyef-react-component](https://github.com/lyef/lyef-react-component).

To know more about the architecture or if you want to contribute with this component:
[Contributing Documentation](https://github.com/<%= authorName %>/<%= appName %>/blob/master/CONTRIBUTING.md).

## License

[MIT License](https://github.com/<%= authorName %>/<%= appName %>/blob/master/LICENSE.md) @ [<%= authorName %>](https://<%= authorName %>.github.io/)
