# BTW is a Babel-Typescript-Webpack boilerplate

Just something ~~simple~~ to get the initial config phase out of the way and just start hacking away.

The plan is to have configurations for things like babel, eslint and prettier done and ready, mainly using `recommended` configs or similar industry standard configs like `eslint-config-airbnb`.

Webpack is as webpack does, so we want to make it as easy to use as possible. Prod/Dev/CI modes, readable sourcemaps without unnecessary `harmony...` artifacts, sensible module aliases

Typescript is essentially our default language which is a good thing, but the various projects tend to have widely differing tsconfigs. Essential options like `noImplicits`, the various `strict` checks, `esnext` target/libs should be standardised. Custom type declarations are also a sore point.

### This boilerplate contains the following buzzwords
- babel7
- typescript
- eslint
- prettier
- webpack
- dotenv
- circleCI

## Is this only for Single-Page-Apps?

The idea for this repo did come from frustrations tweaking the various settings in SPAs but it should be usable for non-SPAs too.
