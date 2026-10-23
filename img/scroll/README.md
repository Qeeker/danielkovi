# Dynamic parchment box kit

Open `index.html` in a browser. Copy `scroll-full.png` and CSS from the example to your project.

The nine extracted PNGs (`top-left`, `top`, `top-right`, `left`, `center`, `right`, `bottom-left`, `bottom`, `bottom-right`) are included for custom 9-patch/grid implementations.

For simplest implementation, use CSS `border-image` with the single `scroll-full.png` and `border-image-slice: 225 265 225 265 fill`. The `fill` keyword renders the center. Keep content in an inner `.scroll__content` element. Horizontally and vertically repeated/stretching edge artwork may distort for especially long or wide content; consider `border-image-repeat: round` if desired.

The source illustration had a dark backdrop; it was converted to transparency. Borders and proportions were regenerated from the scroll artwork with its speech-tail removed.
