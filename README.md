**WORK IN PROGRESS: DO NOT USE YET**

# A straightforward component to filter and sort tables

[![Latest Version on NPM](https://img.shields.io/npm/v/vue-table-component.svg?style=flat-square)](https://npmjs.com/package/vue-table-component)
[![Software License](https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square)](LICENSE.md)
[![Build Status](https://img.shields.io/travis/spatie/vue-table-component/master.svg?style=flat-square)](https://travis-ci.org/spatie/vue-table-component)

Example html:

```html
<table-component
     :data="[
     { id: 1, firstName: 'John', lastName: 'Lennon', instrument: 'Guitar', editUrl: '<a href='#john'>Edit</a>', birthday: '04/10/1940', songs: 72 },
     { id: 2, firstName: 'Paul', lastName: 'McCartney', instrument: 'Bass', editUrl: '<a href='#paul'>Edit</a>', birthday: '18/06/1942', songs: 70 },
     { id: 3, firstName: 'George', lastName: 'Harrison', instrument: 'Guitar', editUrl: '<a href='#george'>Edit</a>', birthday: '25/02/1943', songs: 22 },
     { id: 4, firstName: 'Ringo', lastName: 'Starr', instrument: 'Drums', editUrl: '<a href='#ringo'>Edit</a>', birthday: '07/07/1940', songs: 2 },
     ]"
     sort-by="songs"
     sort-order="asc"
     >
     <table-column show="firstName" label="First name"></table-column>
     <table-column show="lastName" label="Last name"></table-column>
     <table-column show="instrument" label="Instrument"></table-column>
     <tabe-column show="songs" label="Songs" data-type="numeric"></table-column>
     <table-column show="birthday" label="Birthday" data-type="date:DD/MM/YYYY"></table-column>
     <table-column show="editUrl" label="" :sortable="false" :filterable="false"></table-column>
 </table-component>
```

## Demo

Add a link to a site where the component is being demonstrated live.

## Postcardware

You're free to use this package (it's [MIT-licensed](LICENSE.md)), but if it makes it to your production environment we highly appreciate you sending us a postcard from your hometown, mentioning which of our package(s) you are using.

Our address is: Spatie, Samberstraat 69D, 2060 Antwerp, Belgium.

All postcards are published [on our website](https://spatie.be/opensource/postcards).

## Installation

You can install the package via yarn:

```bash
yarn add vue-table-component
```

or npm:

```bash
npm install vue-table-component --save
```

## Usage

Add instruction on how the package can be used

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

```bash
yarn test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) for details.

## Security

If you discover any security related issues, please contact freek@spatie.be instead of using the issue tracker.

## Credits

- [Freek Van der Herten](https://github.com/freekmurze)
- [All Contributors](../../contributors)

## About Spatie
Spatie is a webdesign agency based in Antwerp, Belgium. You'll find an overview of all our open source projects [on our website](https://spatie.be/opensource).

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
