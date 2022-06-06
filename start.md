---
---

## Install Cobalt

First of all, you need Cobalt. If you have Rust toolchain installed,
the easiest way of installing is by running:

    cargo install cobalt-bin

If you don't have a Rust toolchain, see
[Cobalt's site on how to install](http://cobalt-org.github.io/getting-started/).

## Use this site as a starting point (recommended)

This is the easiest way to start. Just clone the repository and edit this site.

```
git clone https://github.com/aljazerzen/cobalt-theme-water.git
mv cobalt-theme-water my-site
cd my-site
cobalt serve
```

These commands will clone the repo, rename it and start a local server.
You should now be able to access your site at <http://localhost:3000>.

## Start a new site

Alternatively, you can copy `_includes` and `_layouts` directories to your site and that's it!

```rust
git clone https://github.com/aljazerzen/cobalt-theme-water.git
mkdir my-site
cp -r cobalt-theme-water/_includes cobalt-theme-water/_layouts my-site/
cd my-site
cobalt serve
```

> At the time of writing, Cobalt does not yet support themes. See [#301](https://github.com/cobalt-org/cobalt.rs/issues/301).


For more information on how to use Cobalt, visit <http://cobalt-org.github.io/>.