# AcMailer (alias)

This is just a helper package designed to alias the `acelaya/acmailer` package name to `acelaya/zf2-acmailer` in packagist.

You can go to [AcMailer](https://github.com/acmailer/acmailer) to see the repository containing the actual code.

## Why

Due to some security restrictions of composer and packagist, it is not possible to rename a package that has already been published.

AcMailer was first released several years ago, in 2012, when Zend Framework 2 was the latest version of what's today known as [Laminas](https://getlaminas.org/).

Since it was initially designed as a ZF2 module, I named it `zf2-acmailer`. It was obviously a bad idea.

The name of the package was already wrong when the new and shiny Zend Framework 3 was released, and now with the re-brand to Laminas, the name is plain wrong.

Because of that, and in order to avoid loosing all the history in packagist, I have decided to publish this small package, which requires `acelaya/zf2-acmailer` and replaces it, so that you can install `acelaya/acmailer` (which is a more generic and future-proof name) and still get the same.
