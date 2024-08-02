# Prettier Lines Before Headings

A [Prettier](https://prettier.io/) plugin to add blank lines before Markdown headings for better readability.


## Install

```sh
npm install --save-dev prettier-lines-before-headings
```

```sh
pnpm add --save-dev prettier-lines-before-headings
```

```sh
yarn add --dev prettier-lines-before-headings
```


## Usage

```json
{
  "tabWidth": 2,
  "trailingComma": "none",
  "linesBeforeHeadings": 2,
  "plugins": ["prettier-lines-before-headings"]
}
```


## API


### `linesBeforeHeadings`

**type**: `number`

**default**: `1`

How many lines to add before Markdown headings.

```
"linesBeforeHeadings": 2,
```
