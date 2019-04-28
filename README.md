# Zocial CSS Social Buttons

The idea is to create beautiful social buttons using only CSS, rendering popular social icons as a font, and requiring minimal extra markup.

## Benefits

- Buttons always look sharp at any size and screen resolution.
- Easily customize the size and call to action of the buttons.
- Easily localize button text to other languages.

## Usage

1. Can be any element e.g. `a`, `div`, `button` etc.
2. Add class of `.zocial` and add class for name of service e.g. `.dropbox`, `.twitter`, `.github`
3. Optional: Add a class of icon to display as icon instead of button
4. Optional: Change font size of the element to resize button

There's also a LESS version from @gustavohenke [here](https://github.com/gustavohenke/zocial-less)

## Examples:

```html
<button class="zocial facebook">Sign in with Facebook</button>
```

or

```html
<a class="zocial twitter">Follow Me</a>
```

## Demo
[https://smcllns.github.io/css-social-buttons/](https://smcllns.github.io/css-social-buttons/)

## Browser Support

- custom font file for all social icons works well in any browser supporting @font-face
- icon font use private unicode spaces for accessibility
- CSS3 degrades gracefully in IE8 and below

## CDN

This project is available on CDNJS:
https://cdnjs.com/libraries/css-social-buttons

## How to contribute

1. Install [Font Custom](https://github.com/FontCustom/fontcustom)
2. Add new font in the `src/` folder.
3. Set color settings in the `templates/zocial.css` file.
4. Run `fontcustom compile`
5. Update the `sample.html` file with both the button and icon.
6. Test rendering. If broken go to step 2.
7. Send pull-request !

## License

Under [MIT License](http://opensource.org/licenses/mit-license.php)

The GitLab logo is derived from [this](https://gitlab.com/gitlab-com/gitlab-artwork/blob/a3aaa39c184e49bb3a0ba0d8be74718b3d5b887b/logo/logo-square.svg) which is released under CC BY-NC-SA 4.0.
