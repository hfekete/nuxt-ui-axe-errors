# components-axe-errors

This repo is for reproducing accessibility issues with components we use.
Errors are reported by cypress-axe plugin using cypress for tests.

To run the tests:

* change into nuxt-app dir ``` cd nuxt-app ```
* do pnpm install ``` pnpm i ```
* do pnpm run dev ``` pnpm dev ```
* and in another window run cypress tests
  1) windowless ``` pnpm test:e2e:chrome ```
  2) or with cypress window manager ``` pnpm test:e2e ``` 
