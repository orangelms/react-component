# @fe-rc/switch

Switch ui component for react.

[![NPM version][npm-image]][npm-url]
[![npm download][download-image]][download-url]

[npm-image]: https://img.shields.io/npm/v/@fe-rc/switch.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@fe-rc/switch
[download-image]: http://img.shields.io/npm/dm/@fe-rc/switch.svg?style=flat
[download-url]: https://npmjs.org/package/@fe-rc/switch

## Install
```
npm i @fe-rc/switch -S
```

## Usage

```js
import Switch from '@fe-rc/switch';

export default () => <Switch />;
```

## API

| Property       | Type                     | Default   | Description                                              |
| -------------- | ------------------------ | --------- | -------------------------------------------------------- |
| prefixCls      | String                   | rc-switch |                                                          |
| className      | String                   | ''        | additional class name of root node                       |
| checked        | boolean                  | false     | whether switch is checked                                |
| defaultChecked | boolean                  | false     | whether switch is checked on init                        |
| onChange       | Function(checked, event) |           | called when switch is checked or unchecked               |
| tabIndex       | number                   |           | tab-index of switch node                                 |
| onClick        | Function(checked, event) |           | called when switch is clicked                            |
| autoFocus      | boolean                  |           | get focus when mounts                                    |
| disabled       | boolean                  | false     | whether switch is disabled                               |
| loadingIcon    | React.ReactNode          |           | specific the extra node. generally used in loading icon. |

## Development

```
npm install
npm start
```

## License

 MIT license.
