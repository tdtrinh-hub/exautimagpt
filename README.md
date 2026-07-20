# Autima

Batch image generation for ChatGPT — attach one or two reference images, queue a
list of prompts, and let it run each prompt through ChatGPT and save every
generated image to your Downloads folder.

This repository hosts the **privacy policy** for the Autima Chrome
extension. (The repo/URL keep the legacy `exautimagpt` name so the published
link stays stable; the product is **Autima**.)

- **Privacy policy:** <https://tdtrinh-hub.github.io/exautimagpt/>

> **Maintenance rule:** review this policy on **every new extension version**
> before publishing. If a release changes behavior, permissions, data handling,
> or the download location, update `index.html` accordingly and bump its
> "Last updated" date. If nothing relevant changed, no edit is needed. (Mirrored
> in the extension repo at `py_tools/docs/autima-market/DECISION.md` D-002.)

## About the extension

Autima automates image generation on the ChatGPT website
(`chatgpt.com`). You provide one reference image (or two, to combine) and a
queue of prompts — typed, imported from a JSON file, or generated with ChatGPT's
help — and the extension sends each prompt with your image attached, waits for
the result, and saves the PNG automatically. It runs in a side panel next to
ChatGPT, with live per-prompt status and a Stop control.

It runs entirely in your browser, using your own logged-in ChatGPT session.
There are no servers, no accounts, and no analytics or tracking — nothing is
collected or transmitted to the developer. See the privacy policy above for
details.

---

Autima is an independent tool and is not affiliated with, endorsed by, or
sponsored by OpenAI. "ChatGPT" is a trademark of OpenAI.
