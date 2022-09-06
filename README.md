# homebrew-webdiff

Homebrew Formula for [webdiff].

To install, run:

    brew install danvk/webdiff/webdiff

Steps to create this using [pypi-poet]:

    python3 -m venv venv
    source venv/bin/activate
    pip install webdiff homebrew-pypi-poet
    poet -f webdiff > webdiff.rb

Then edit as needed. Due to system dependencies, Homebrew pillow is preferable to PyPI pillow.
ImageMagick is a recommended dependency for webdiff and is marked as such.

[pypi-poet]: https://github.com/tdsmith/homebrew-pypi-poet
[webdiff]: https://github.com/danvk/webdiff
