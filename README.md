# WordPress Skeleton

Framework for starting development on a new WordPress site. Thanks to [Mark Jaquith](https://github.com/markjaquith/WordPress-Skeleton) for the inspiration!

## Assumptions

* WordPress as a Git submodule in `/wp/`
* Custom content directory in `/content/` (cleaner, and also because it can't be in `/wp/`)
* `wp-config.php` in the root (because it can't be in `/wp/`)
* All writable directories are symlinked to similarly named locations under `/shared/`.