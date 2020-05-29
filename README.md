# Brazilian Portuguese Messages for React-Admin

## Note:

This project is a **temporary fork** based on the great work made by @gucarletto in his [ra-language-pt-br](https://github.com/gucarletto/ra-language-pt-br/) repository.

Reason: the published package is [not working properly](https://npm.runkit.com/ra-language-pt-br), so I have forked and adapted it to be able to create and publish the npm package again, see [issue](https://github.com/gucarletto/ra-language-pt-br/issues/1).

---

Brazilian Portuguese messages for [react-admin](https://github.com/marmelab/react-admin), the frontend framework for building admin applications on top of REST/GraphQL services.

[![react-admin-demo](https://marmelab.com/react-admin/img/react-admin-demo-still.png)](https://vimeo.com/268958716)

## Installation

```sh
npm install --save @denisazevedo/ra-language-pt-br
```

## Usage

```js
import ptBrMessages from '@denisazevedo/ra-language-pt-br';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'pt-br': ptBrMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="pt-br" i18nProvider={i18nProvider}>
  ...
</Admin>
```

## License

This translation is licensed under the MIT License.
