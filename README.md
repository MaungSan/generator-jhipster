## Install JHipster/FountainJS POC

## Get FountainJS

1. `git clone git@github.com:FountainJS/fountain.git`
2. `cd fountain && git submodule update --init --recursive`
3. For the following repos, run `cd $ && git checkout poc-jhipster`
	- `fountain-generator`
	- `generator-fountain-angular2`
	- `generator-fountain-browsersync`
	- `generator-fountain-gulp`
	- `generator-fountain-systemjs`
	- `generator-fountain-webpack`
4. `cd .. && node scripts/links` to make every generator available in the global npm

## Get JHipster

1. `git clone git@github.com:FountainJS/generator-jhipster.git`
2. `git checkout poc-fountain-angular2`
3. `npm link`
4. In order to use local `fountain-angular2`, run `npm link generator-fountain-angular2`


## Use FountainJS/JHipster

1. Run `yo jhipster`. Now the `Angular 2` option has been replaced by FountainJS Angular 2 generator.
2. Run `gulp serve`
