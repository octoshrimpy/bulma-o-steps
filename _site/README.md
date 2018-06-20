# Steps component for Bulma

This is an extension for the [Bulma CSS Framework](http://bulma.io).  

It adds an in-depth `steps` component to track progress in multi-step forms or wizards.  
Original written by [aramvisser](https://github.com/aramvisser) over at [his original repo](https://aramvisser.github.io/bulma-steps)

[![Steps example for a checkout form](steps-example.png)](https://octoshrimpy.github.io/bulma-o-steps)

## Documentation

[Usage & Examples](https://octoshrimpy.github.io/bulma-o-steps)

I'm trying to keep this working with the latest available Bulma version.     
Currently tracking: **bulma v0.7.1**. Other versions _should_ work, but no promises.

## Installation

### NPM

`npm install bulma-o-steps`

### Manually

#### SASS
- Download the `bulma-steps.sass` file
- Add `@import "bulma-steps.sass"` _after_ the `@import "bulma.sass"` statement in your own
  stylesheet

#### CSS
- Download the `bulma-steps.min.css` file
- Add `@import "bulma-steps.min.css"` _after_ the `@import "bulma.css"` statement in your own
  stylesheet   
- An expanded version of the file is also available at `bulma-steps.css`

#### Hosted Online
Alternatively, you can include bulma and bulma-steps from a CDN.   
As of writing, these are the current CDNs for both:
- bulma: https://cdnjs.cloudflare.com/ajax/libs/bulma/0.7.1/css/bulma.min.css
- bulma-steps: https://cdn.rawgit.com/octoshrimpy/bulma-o-steps/master/bulma-steps.css

## Development

This repository doubles as the documentation page using Jekyll. You can see changes in the
documentation by running Jekyll locally.

- Install ruby and then install Jekyll with `gem install jekyll`
- Ruby's eventmachine is broken in windows, you can fix it by uninstalling it with `gem uninstall eventmachine` and reinstalling the proper one with `gem install eventmachine --platform ruby`
- Clone this repository
- Run `jekyll serve` inside the root directory of this repository. Use ` --livereload` if you'd like to see the changes live.
- Open the documentation page on [http://localhost:4000](http://localhost:4000)
- Make changes to the `bulma-steps.sass` file
- Reload the documentation page to see your changes

## Related Project

There is another steps extension by
[Wikiki](https://github.com/Wikiki/bulma-steps),
and the original source of this one, by [aramvisser](https://aramvisser.github.io/bulma-steps)
