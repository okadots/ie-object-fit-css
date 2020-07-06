# IE11 Object Fit CSS, to extend Object Fit Images by Fregante.

The purpose of this repo is to assist in supporting `object-fit` and `object-position` in IE11 using [TailwindCSS](https://tailwindcss.com/). 

To use:
1. [Enable](https://github.com/tailwindcss/tailwindcss/pull/1635) `target:ie11` in your Tailwind config. This removes the `object-fit` related classes.
2. Add `object-fit-polyfill` to your css, make sure it is included after the Tailwind utilities.
3. Install [object-fit-images](https://github.com/fregante/object-fit-images). You will not need to make any css changes as `object-fit-polyfill` in this repo already provides the necessary changes.

Note: Depending on the javascript your project is using, IE11 may not support it.  Ensure that your javascript is working properly otherwise this won't work!

