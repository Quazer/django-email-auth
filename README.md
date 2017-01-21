![MIT license](https://img.shields.io/badge/licence-MIT-blue.svg)
![Stable](https://img.shields.io/badge/status-stable-green.svg)

# django-emailauth

Django 1.10 User model with email instead of username.

This app fully integrates with Group, Permission and Admin.


## Installation 

Clone the repo:

`git clone https://github.com/charlesthk/django-email-auth.git`


Add `emailauth` to your `INSTALLED_APP` setting:

```python
INSTALLED_APPS = (
    ...
    'emailauth',
)
```

Add `AUTH_USER_MODEL` setting :

```python
AUTH_USER_MODEL = 'emailauth.User'
```

Run migrations :

```
./manage.py makemigrations
./manage.py migrate
```

Your are now good to go !


## Support

If you are having issues, please let us know or submit a pull request.

## License

The project is licensed under the MIT License.