# Homework

- Create the `goit-markup-hw-4` repository;
- Clone the created repository and copy the files of the previous work into it.
- Add markup and styling for icons and decorative effects for pages from the layout
  [homework #5.](<https://www.figma.com/file/0uRxYENU9pFeOsq0U0u4IJ/Web-Studio-(Version-2.1)-(Copy)?node-id=1-836&t=3q4RZmJqj7UTH92c-0>)
- Set up `GitHub Pages` and add a link to the live page in the header of the GitHub repository.

## Eligibility criteria for a mentor

### Project

**`«A1»`** All styles are written in one `style.css` file, which is located in the `css` folder.

**`«A2»`** Source code formatted with `Prettier`.

**`«A3»`** All images and text content are taken from the layout.

**`«A4»`** [Modern-nomalize](https://github.com/sindresorhus/modern-normalize) style normalizer is
enabled on all HTML pages.

**`«A5»`** The code is written following the [manual](https://codeguide.co/).

**`«A6»`** The modal window script is connected in HTML by a separate `modal.js` file.

### Markup

**`«B1»`** Completed HTML markup of all layout elements.

**`«B2»`** Tags are used according to their semantic meaning.

### Decor

**`«C1»`** Transitions have been made for all hover and focus effects (color, background, shadow).
Time - `250ms`, time distribution function - `cubic-bezier(0.4, 0, 0.2, 1)`.

**`«C2»`** Transitions and animations explicitly specify the properties to be animated. There is no
`all` value anywhere.

**`«C3»`** In the `What We Do` section, text with a background is positioned on top of the image.

**`«C4»`** In the main navigation, using the `::after` pseudo-element, the link of the current page
(on which the user is currently located) is underlined.

**`«C5»`** A blue overlay with text on the cards of the `Portfolio` page appears on hover anywhere
in the card.

**`«C6»`** The blue overlay in the `Portfolio` page cards slides out from the bottom, as shown in
the [video](https://github.com/goitacademy/html-css-homework/blob/master/05-preview.gif).

**`«C7»`** Pseudo-elements do not have text content in the `content` property. They are used solely
for decorative purposes.

### Modal window

**`«D1»`** The layout and design of the "backdrop" (dark translucent background) of the modal window
has been completed.

**`«D2»`** The "backdrop" fills 100% of the height and width of the browser viewport and is fixed in
it.

**`«D3»`** The layout and design of the modal window has been completed.

**`«D4»`** The modal window is vertically and horizontally positioned in the middle of the backdrop.

**`«D5»`** The layout and design of the close button of the modal window in the upper right corner
has been completed.

**`«D6»`** Initially, the modal and the backdrop are hidden using the `is-hidden` class on the
backdrop, whose selector uses the `visibility`, `opacity`, and `pointer-events properties`.

**`«D7»`** If you remove the `is-hidden` class from the backdrop, a backdrop and a modal window
appear.

**`«D8»`** The appearance and disappearance of the modal is animated by a transition with an
arbitrary effect, such as `scale` or `translate`, and `opacity`.
