
# George Lambert Potato Assignment

## Setup

- there were a couple of things not listed in `Tasks - bugs` which I fixed in order to allow the development server to run:

  * I added `CRISPY_ALLOWED_TEMPLATE_PACKS = ('bootstrap', 'uni_form', 'bootstrap3', 'foundation-5')` to `settings.py` in order to render crispy forms.
  * I created an `appengine_config.py` file to prevent a local configuration error that was throwing the following error `ImportError: No module named msvcrt`.

## Tasks - bugs and new features

- bug fixes and new features are detailed in my commits.