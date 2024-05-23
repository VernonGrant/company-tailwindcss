# Company Tailwindcss

Provides basic completions for Tailwindcss

## Installation

### Manual installation on Emacs 29.1 and up

Add the following to your init file. It will basically download and install the package automatically.

```lisp
(unless (require 'company-tailwindcss nil 'noerror)
  (package-vc-install
   '(company-tailwindcss :url "https://github.com/VernonGrant/company-tailwindcss"
              :branch "main"
              :main-file "company-tailwindcss.el")))
```

And if your using Eglot, set the following config option:

```lisp
(setq eglot-stay-out-of '(company))
```
