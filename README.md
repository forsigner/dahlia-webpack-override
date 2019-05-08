# dahlia-plugins

## Installation

```sh
yarn add dahlia-less dahlia-antd
```

## Usage

```js
import less from 'dahlia-less'
import antd from 'dahlia-antd'

export default {
  plugins: [
    less({
      modifyVars: {
        'primary-color': 'red',
        'link-color': '#1DA57A',
        'border-radius-base': '10px',
      },
      javascriptEnabled: true,
    }),
    antd(),
  ],
}
```

## License

[MIT License](https://github.com/forsigner/dahlia-plugins/blob/master/LICENSE)
