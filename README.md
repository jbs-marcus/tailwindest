# Boost up tailwindcss DX

<div align="center">

<img src="./assets/tailwindest.banner.png" width="525" alt="tailwindest banner" />

<br />
<br />

**Fully typed className package** for the **`tailwindcss`**

<br />

</div>

```ts
const helloBox = wind({
    display: "flex",
    alignItems: "items-center",
    justifyContent: "justify-center",

    padding: "p-4",
    margin: "m-4",

    borderRadius: "rounded-md",
    backgroundColor: "bg-white",
    "@dark": {
        backgroundColor: "dark:bg-neutral-900",
    },
}).class()
```

<br />

# Design Goals

> Make
> **_Readable_** / **_Reusable_** / **_Flexible_**
> className

<br />

# Recommended for

1. Strictly **typed** **`tailwind`**
2. Love **css in js like syntax**
3. Make **design system with** **`tailwind`**
4. **Refactoring** lover

<br />

# Worth it?

## 🏛️ Fully typed

> **Autocompleted** by **`typescript`**, **`tailwind`** is literally insane.

## 💅 Similar to css in js

> Syntax is **very similar to css in js**, meaning **easy to use it.**

## 🔮 Variants

> **Variants based conditional styling**, Inspired by **`stitches`** & **`vanilla-extract`**
>
> Practical and Intuitive.

## 🧬 Official Document

> **Hover** the property, you will **get document** **`link`**.
>
> <img src="./assets/docs.png" width="420" />

## 🍦 Atomic Size

> Gzip, **`614B`** **_tiny_ library**.
>
> Don’t worry about bundle size.

## 🔌 Custom value? Yeas.

> **Support extended custom values**, defined in **`tailwind.config.js`**.

## 🔥 Combine Power of Inline & Tailwindest

> **Short / Simple style**
> = pure **`inline class`**
>
> **Complex / Conditional style**
> = **`tailwindest`**

<br />

# Start

```bash
pnpm i tailwindest
```
