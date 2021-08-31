# builtin-url

This simply exports the appropriate WHATWG URL implementation given the
platform. As such, and by design, it does not contain any shims. So if you're
running node prior to version 8, or on an ancient browser that doesn't support
the URL API, it simply won't work. If you're looking for that see the
`universal-url` package.

## Licenses

The package itself is under the Unlicense, in so far a copyright can apply to
something that's arguably no a creative work.

It also contains an extract of the [Typescript](https://github.com/Microsoft/TypeScript) type definitions - these are under the Apache 2.0 license.
