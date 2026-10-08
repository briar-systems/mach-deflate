# mach-deflate

<p>
  <a href="https://github.com/briar-systems/mach-deflate/actions/workflows/ci.yml"><img src="https://github.com/briar-systems/mach-deflate/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="LICENSE"><img src="https://img.shields.io/github/license/briar-systems/mach-deflate?color=FF00FF&labelColor=000000" alt="License"></a>
</p>

**A Mach library for DEFLATE (RFC 1951) compression and decompression, the zlib (RFC 1950) and gzip (RFC 1952) framings, and the adler32 and crc32 checksums.**

## Usage

Add the dependency to `mach.toml`:

```toml
[dep.deflate]
git = "https://github.com/briar-systems/mach-deflate"
version = "^0.1"
```

Then bind the library in a source file:

```mach
use deflate;
```


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
