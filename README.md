# Django Issues
Here is a demo repo for testing errors with third-party packages for django and DRF.

## How To

Each issue should be its own branch, copied from the base `main` branch. The `main` branch has a 
simple enough base API that should cause no problems with any packages.

## Branch Naming

For each issue, create a new branch, with the format:

```
<package-name>-python<python-version>-django<django-version>-drf<drf-version>-<issue_name_snake_case>
```
For example, a branch that demonstrates a auth error with the `drf_spectacular` package, with python 3.11, django 4.2.7, and drf 3.14.0 would be:

```
drf_spectacular0.26.5-custom_auth_error-python3.11-django4.2.7-drf3.14.0-custom_auth_error
```

You can create different branches for different versions if there are noticeable differences. You should use the latest version that demonstrates the error. If you are having issues with mutliple packages, they should be listed first, separated by a dash.