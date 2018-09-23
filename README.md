
# PrimeNG

Fork of PrimeNG

## How to build a new release

- gulp build-assets
- gulp build-exports
- ./node_modules/.bin/ngc --p tsconfig-aot.json
- ./node_modules/.bin/tsc --p tsconfig-aot.json
- npm publish



