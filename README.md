> [!NOTE]
> As you might already know,  
> **Pico CSS is [officially](//picocss.com/docs/maintenance) no longer maintained — <mark>but:</mark>**

## Development continues under [Blades CSS](//github.com/anyblades/blades)

| Homepage:             | https://blades.dev/                                    |
| --------------------- | ------------------------------------------------------ |
| Documentation:        | https://blades.dev/#docs                               |
| Source code:          | https://github.com/anyblades/blades                    |
| Underlying Pico fork: | https://github.com/anyblades/blades/tree/main/src/pico |

## What's fixed?

Blades focuses exclusively on the `pico.css` version, similar to how [simple.css](https://github.com/kevquirk/simple.css) is maintained (for Sass version check [@Yohn's fork](https://github.com/Yohn/PicoCSS) instead).

Pico issues fixed in Blades:

- [#738 🐞 Submit button margin affecting siblings within .grid](https://github.com/picocss/pico/issues/738)
- [#734 🐞 RTL breadcrumbs add weird backslashes](https://github.com/picocss/pico/issues/734)
- [#733 🐞 Fix for datetime input width within groups within grids on medium breakpoint](https://github.com/picocss/pico/issues/733)
- [#731 🛠️ Allow to selectively unreduce motion like `[aria-busy="true"]` does](https://github.com/picocss/pico/issues/731)
- [#727 🐞 Fix dropdown summary ul offscreen](https://github.com/picocss/pico/pull/727) (Safari)
- [#721 🛠️ Possible duplicate of text-align property inside the same element selector](https://github.com/picocss/pico/issues/721)
- [#701 🐞 Nav dropdowns display error with Firefox](https://github.com/picocss/pico/issues/701)
- [#696 🛠️ Missing styling for `<var>` element](https://github.com/picocss/pico/issues/696) + [#695](https://github.com/picocss/pico/discussions/695)
- [#670 🐞 Slow website picocss.com](https://github.com/picocss/pico/issues/670) + [#718](https://github.com/picocss/pico/pull/718) (`box-shadow` performance issues)
- [#513 🐞 Image element attribute height is overridden](https://github.com/picocss/pico/issues/513)

See fixes in action:

1. Demo: [@picocss/pico issues reproduced](https://codepen.io/anydigital/full/WbGgbJd) (where applicable)
2. Demo: [@anyblades/blades running without issues](https://codepen.io/anydigital/full/YPGOXWV) (on exact same markup!)

Every Blades build includes the actual `.diff` with exact changes against "canonical" `pico.css`:

- https://github.com/anyblades/blades/blob/main/css/pico.css.diff
- https://github.com/anyblades/blades/blob/main/css/pico.min.css.diff

## What's new?

See https://blades.dev/#docs marked with <mark>NEW</mark>.

All shipped as `blades.css` — a drop-in compatible replacement for `pico.css`.

## How to migrate?

Just switch `pico.css` to `blades.css`— and voilà!

[**Get started →**](//blades.dev/css/)

<br><br>

# blades<sup>✨</sup> <br><sup><sub>Same spirit, new home.</sub></sup>

🥷

<!--
> [!IMPORTANT]
> **Work in progress** — information below is under review:
-->
