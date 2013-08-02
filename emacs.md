## Emacs
GNU Emacs is an extensible, customizable text editor—and more. [http://www.gnu.org/software/emacs/](http://www.gnu.org/software/emacs/)

### Requirements

* Homebrew

### Installation

```bash
brew install emacs --cocoa --srgb
```

You might want to copy the app into the applications directory, otherwise Spotlight and other similar tools won't be able to see it:

```bash
cp -r /usr/local/Cellar/emacs/24.3/Emacs.app /Applications/
```

### Configuration

The _clojure-mode_, _clojure-test-mode_, _nrepl_ and _paredit-mode_ are essential for a fluid Clojure development. But, from there it's up to you, the options are endless.

You'll have problems with accents given the option key has a special meaning in Emacs. The solution is [here](http://emacsformacosx.com/tips).
