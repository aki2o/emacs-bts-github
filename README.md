# What's this?

This is a extension of Emacs that is a plugin of ![bts.el](https://github.com/aki2o/emacs-bts) for GitHub.  

# Install

### If use package.el

2015/01/06 It's available by using melpa.

### If use el-get.el

2015/01/06 It's available. But, master branch only.

### If use auto-install.el

```lisp
(auto-install-from-url "https://raw.github.com/aki2o/emacs-bts-github/master/bts-github.el")
```
-   In this case, you need to install each of the following dependency.

### Manually

Download bts-github.el and put it on your load-path.  
-   In this case, you need to install each of the following dependency.

### Dependency

-   ![bts.el](https://github.com/aki2o/emacs-bts)
-   ![gh.el](https://github.com/sigma/gh.el)

# Configuration

```lisp
(require 'bts-github)

;; About config item, see Customization or eval the following sexp.
;; (customize-group "bts-github")
```

# Tested On

-   Emacs &#x2026; GNU Emacs 24.3.1 (i686-pc-linux-gnu, GTK+ Version 3.4.2) of 2014-02-22 on chindi10, modified by Debian
-   bts.el &#x2026; 0.0.1
-   gh.el &#x2026; Unknown

**Enjoy!!!**
