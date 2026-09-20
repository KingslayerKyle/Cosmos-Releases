# Cosmos

**A tool that saves the brushwork of a Black Ops III map as a `.map` file you can open in Radiant.**

---

## Getting started

1. Open a game in Cordycep.
2. Run `cosmos.exe`
3. Click **Load game**, then **Export** beside the map you want — or **Export all** for every map
   at once.

**Everything** saves every brush; **Solid only** leaves out the clip and the triggers, which is
usually what you want if you're after the shape of the map.

## Where the files go

Beside `cosmos.exe`, in a folder of their own per map:

```
exported_files/bo3/maps/zm_zod/zm_zod.map
```

**Open export folder** takes you straight there.

## What you get

Every brush the map was built from, at its real size and position — the walls and floors, the clip,
the triggers and the volumes. Each face is named for what it is: `caulk`, `clip`, `clip_ai`,
`clip_vehicle`, `water` or `trigger`.

**Brushes only.** Models, terrain and texture alignment are not part of what's read, so the `.map`
is the shell of the map rather than a copy of it. Every face comes out with Radiant's default
texture placement.

## Supported titles

- Black Ops III

---

## Questions and bug reports

Both are welcome, in [our community Discord](https://discord.gg/tzzn6zAVBz).

---

## Support

Cosmos is free, and built in my spare time. If it's saved you some work, a small tip is genuinely appreciated.

<p align="left">
  <a href="https://paypal.me/kingslayerkyle">
    <img src="https://img.shields.io/badge/Donate-PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="Donate with PayPal">
  </a>
</p>

<p align="left"><sub>Thank you. 💛</sub></p>
