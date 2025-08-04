# ⛔️ **DEPRECATED** — do not use for new projects

See [our current docs](https://docs.apostrophecms.org/)

# apostrophe-address-widgets

An address widget for [ApostropheCMS](http://apostrophecms.org/).

`apostrophe-address-widgets` provides a simple way for users to create an address or for developers to add schema for an address, such as a mailing address.

## Installation

```bash
npm install apostrophe-address-widgets --save
```

## Use

You can use `apostrophe-address-widgets` as you would any widget in ApostropheCMS.

Here's an example of a singleton:

```nunjucks
{{ apos.singleton(data.page, 'address', 'apostrophe-address') }}
```
