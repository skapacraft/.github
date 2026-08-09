# SkapaCraft

Native desktop applications, WordPress plugins and Garmin Connect IQ software,
built on a philosophy of zero bloat and complete transparency.

**SkapaCraft isn't a company. It's a standard**, applied to every tool, every
plugin, every line of code that carries the name.

## The philosophy

Most software today is built to impress on a feature list, not to respect the
person running it. Plugins that bundle a full UI framework for a button. Apps
that phone home before you've even opened the settings screen. Dashboards you
need a manual to understand.

SkapaCraft started as a reaction to that: **what if the default was the
opposite?**

- **Zero bloat** instead of maximum features
- **Privacy by default**, not "we value your privacy" fine print
- **Code you can actually read** instead of a black box you're told to trust

## How things get built here

Every tool that carries the SkapaCraft name follows the same four rules,
regardless of platform:

1. **Performance first, not last.** Speed isn't an optimisation pass at the end;
   it's a constraint from the first line of code.
2. **No bloat.** Every feature needs a reason. If it doesn't pull its weight, it
   doesn't ship.
3. **Transparent by design.** You know what the code does because you can read
   it. Privacy defaults aren't negotiable.
4. **Native, not wrapped.** Built for the platform, not ported from the web or
   buried inside a framework.

## What is published here

### Desktop

| Project | What it is |
|---|---|
| **[Nostos](https://github.com/skapacraft/nostos)** | Brings a Google Takeout export home: writes photo dates and locations back into the images, merges split archives, deduplicates by content. Opens no network connections, and that constraint is enforced in CI. Tauri, Rust and React. GPL-3.0. |

### WordPress plugins

| Project | What it is |
|---|---|
| **[LivQ AccessFix](https://github.com/skapacraft/livq-accessfix)** | Server-side WCAG 2.2 AA and European Accessibility Act fixes, applied to the rendered HTML rather than patched into the DOM afterwards. GPL-2.0. |
| **[Cetus Image Converter & AI Alt Text](https://github.com/skapacraft/cetus-media-optimizer)** | AVIF and WebP conversion for the whole media library, plus alt text generated through Gemini or OpenAI with your own key. Originals are never deleted. GPL-2.0. |

### Garmin Connect IQ

| Project | What it is |
|---|---|
| **[Ultra-Trail Dashboard](https://github.com/skapacraft/ultra-trail-dashboard)** | Data field for trail and ultra running: smoothed grade, Grade Adjusted Pace from the Minetti energy-cost model, and three physiological models that say how long you have left. GPL-3.0. |
| **[Medical ID Wallet](https://github.com/skapacraft/medical-id-wallet)** | Blood type, allergies, medications and emergency contacts on the watch, with a scannable QR or barcode. Fully offline, 20 languages. GPL-3.0. |

Every one of them is open source, and every one ships the same source that the
store binary is built from.

## Getting involved

Bug reports and feature requests belong in the issue tracker of the repository
they concern. Security problems do not: each repository has a **Security** tab
with private reporting, and a `SECURITY.md` saying what counts as one.

Anything else: **info@skapacraft.com**, or [skapacraft.com](https://skapacraft.com).

---

Built with the belief that software should be fast, transparent, and respect the
person running it.
