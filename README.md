# csskit-form

simple css for forms.

## Install

```
npm i --save csskit-form
```

Or just grab the css.

## Usage

If you installed with npm:

- In your main css file: `@import "csskit-form";`
- Use a tool like [sheetify](http://npmjs.org/sheetify) or [rework-npm-cli](http://npmjs.org/rework-npm-cli) to bundle the css.
- Example using npm-rework-cli: `npm-rework main.css -o bundle.css`

### CSS classes:

No need to apply any classes to you input fields for basic usage. If you want to change the size of the input fields you can use these optional classes:


- `.small`- **optional**
- `.medium`- **optional**
- `.large`- **optional**
- `.full-width`- **optional** – centers, makes button full width on mobile

Example:

```
<input type="email" class="small" placeholder="you@example.com">
```

## License
[MIT](/LICENSE.md)