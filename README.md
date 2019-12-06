# Invalid Character Bug Demo

1. Install dependencies with `pipenv`
1. Run `manage.py collectstatic`
1. Fire up the server and open http://127.0.0.1:8000/. In most browsers, you'll see a green "jQuery loaded successfully" message, but in Safari, you'll see "Failed to load jQuery" in red. 
1. Uncomment the last six lines in `settings.py` and try loading the page in Safari again. This time, it should work.
