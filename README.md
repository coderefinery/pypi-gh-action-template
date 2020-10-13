# Github action tempalt to publish to PyPI

Uses https://github.com/pypa/gh-action-pypi-publish

This is a template to copy, so that you don't have to over and over.
Some interesting features:

- Uploads on tags
- Checks that the tag version matches the version in the source code,
  fail otherwise
- Detect module name from current directory name

## Development status

You probably don't want to use this unless you are willing to figure
out some stuff that's wrong.
