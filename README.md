# Marklate — a private, code-safe translator for website & store content

A simple, side-by-side translator built for people who localise **WordPress** and **PrestaShop**
sites and are tired of Google Translate mangling their HTML and shortcodes.

It runs **entirely in your browser** using Chrome/Edge's built-in on-device translation.
No account, no API key, no cost, and nothing is sent to a server — your clients' text
never leaves your machine.

## What makes it different

Most translate boxes give you plain text in, plain text out. This one is built for a specific job:

- **Protects your code.** HTML tags, `[shortcodes]`, and placeholders like `%s`, `{name}` or
  `{{variable}}` are shielded during translation and restored afterwards — so pasting a product
  description or a template string doesn't break your markup.
- **Private and offline.** Translation happens on your device. Good for client work and NDAs.
- **Free forever.** No usage limits, no key, no subscription.
- **Side-by-side and instant.** Translates as you type, like the tools you already use.

## Requirements

- **Chrome 138+** or **Microsoft Edge 148+**, on a **desktop** computer.
- The first time you use a language pair, the browser downloads a small model (one time), then
  it works offline.

## How to use

1. Open the site (or `index.html`).
2. Pick your target language.
3. Type or paste text — the translation appears on the right. Copy it out.

Keep the "Protect code" button on when translating website content. Turn it off for plain prose.

## Publish it online (no build step needed)

It's a single `index.html` file. To put it online for free:

1. Create a free GitHub account and a new **public** repository (e.g. name it `marklate`).
2. Upload `index.html` and this `README.md` (use **Add file → Upload files**).
3. Go to **Settings → Pages**, set the source to your main branch, and save.
4. GitHub gives you a public link in a minute — share it, or install it as an app from Chrome/Edge
   (**⋮ menu → Install this site as an app**).

## Roadmap

This is the free tier. A planned **Pro** tier adds AI-powered features that on-device models can't do:

- Freeform **context/tone** instructions ("keep it persuasive", "formal register").
- A **brand glossary** — lock terms that must stay identical across every page and language.
- Whole-record translation (title + description + meta) in one pass.

## Feedback wanted

If you localise sites for a living, I'd love your input on a few specific things:

- Which **languages** do you translate into most, and does the on-device quality hold up for them?
- What **breaks** when you paste real WordPress/PrestaShop content here? (Open an issue with an example.)
- What single feature would make you **choose this over DeepL or Google** for your workflow?

Open an issue or a pull request. Please keep suggestions tied to a concrete task you actually do.

## License

MIT — see the [LICENSE](LICENSE) file. Use it, fork it, ship it.
