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
ref = "branch/dev"
```

Then bind the library in a source file:

```mach
use deflate;
```

The library forwards these modules:

- `deflate.deflate`: DEFLATE compression (RFC 1951)
- `deflate.inflate`: DEFLATE decompression (RFC 1951)
- `deflate.zlib`: the zlib framing (RFC 1950)
- `deflate.gzip`: the gzip framing (RFC 1952)
- `deflate.format`: the DEFLATE tables shared by compression and decompression
- `deflate.adler32`: the Adler-32 checksum
- `deflate.crc32`: the CRC-32 checksum


## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for building, testing and the contribution rules.


## License

[MIT](LICENSE)
