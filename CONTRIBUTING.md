# Contributing

Thank you for your interest in contributing! Please feel free to put up a PR for any issue or feature request.
Even if you have little to no experience with Angular 2, I'll be more than happy to help. :)

## Setup

1. Fork the repo
2. Clone your fork
3. Make a branch for your feature or bug fix
4. If you don't have Angular CLI installed: `npm install -g angular-cli@latest`
5. `ng init`
6. Input `n` for each file to not overwrite any file changes
7. Run `npm build` to check if a build works (if this doesn't work, please file an issue with your error message)
8. Run `ng serve` and open `localhost:4200` in a browser
9. Work your magic
10. Run `ng build --prod --aot` or `ng serve --prod --at` to kick off a production build and make sure nothing is broken
11. To test service worker changes:
  * `npm run sw` to generate the service worker file
  * `npm run static-serve` to load the application along with the service worker asset using [lite-server](https://github.com/johnpapa/lite-server)
12. Commit your changes and reference the issue you're addressing (for example: `git commit -am 'Commit message. Closes #5'`)
14. Push your branch to your fork
14. Create a pull request from your branch on your fork to `master` on this repo
15. Have your branch get merged in! :star2:

If you experience a problem at any point, please don't hesitate to file an issue!
