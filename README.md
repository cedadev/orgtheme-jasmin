# orgtheme-jasmin

Bootstrap 5 organisation theme (colour scheme) for JASMIN web components.

The demo page demo/index.html provides examples of typography, layout styles and functional elements which can be used to construct templates.

It is not, itself, a template.

## Installation

For development purposes, the theme can be installed as follows. For production purposes it should be linked to in-place on the CEDA artefacts server.

`orgtheme-jasmin` can be installed directly from Github using pip, e.g. into an existing `venv` for development, but for production the current version should be referenced on the ceda artefacts server.

```
$ virtualenv --no-site-packages ./venv
$ source ./venv/bin/activate
$ pip install git+https://github.com/cedadev/orgtheme-jasmin.git
```
It is intended to be used as a building bock for subsequent framework (e.g. Django) and individual application customisations.

# Building/Upgrading
* Install the dependencies with `npm install`.
* Bump the theme version in package.json.
* Run `npm run build` to make build of the theme in /build, including compiled sass, assests and vendored dependencies.
