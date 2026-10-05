<!-- tyhp-readme:start -->
# tyhpdef/staudenmeir-belongs-to-through

Tyhp type definitions for `staudenmeir/belongs-to-through` `2.18`.

```bash
composer require --dev tyhpdef/staudenmeir-belongs-to-through:2.18
```

This is a metapackage. Composer also installs `tyhpdef/staudenmeir-belongs-to-through-impl` (type files).
Require **this** name, not `tyhpdef/staudenmeir-belongs-to-through-impl`.

See https://tyhplang.com.

## Maintain `staudenmeir/belongs-to-through`? Ship the types yourself

If you are a Packagist maintainer of `staudenmeir/belongs-to-through`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/staudenmeir-belongs-to-through-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `staudenmeir/belongs-to-through` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/staudenmeir-belongs-to-through": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `staudenmeir/belongs-to-through` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `staudenmeir/belongs-to-through` with a real constraint,
   `"replace": { "tyhpdef/staudenmeir-belongs-to-through": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `staudenmeir/belongs-to-through` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/staudenmeir-belongs-to-through` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
