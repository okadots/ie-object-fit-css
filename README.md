# ie-object-fit-css

The purpose of this repo is to assist in supporting `object-fit` and `object-position` in IE11 using [TailwindCSS](https://tailwindcss.com/).

To use:
1. [Enable](https://github.com/tailwindcss/tailwindcss/pull/1635) `target:ie11` in your Tailwind config. This removes the `object-fit` related classes.
2. Add `o

//target ie11 is enabled which removes the object-fit and object-fit classes as they are not supported in ie11
//this scss file is meant to replace those so the other functionality of the tailwind targets are still usable
//also using postcss-object-fit-images and object-fit-images polyfills to support object-fit and object-position in ie11
//postcss-object-fit-images does not currently support the object-position classes and will not support custom object postions (eg. from focal point)
