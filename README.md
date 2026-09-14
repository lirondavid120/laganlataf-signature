# laganlataf-signature

Public image assets for the "לגן ולטף" (Lagan Lataf) HTML email signature.

Files live in `img/` and are served over HTTPS via GitHub Pages:

    https://lirondavid120.github.io/laganlataf-signature/img/

| File | Size | Notes |
|---|---|---|
| `laganlataf_logo.gif` | 300x101 | Animated. First frame is the complete logo on purpose, so Outlook desktop (which renders only frame 1) still shows the full logo. |
| `icon_mail.png` | 56x56 | Displayed at 20x20 in the signature. |
| `icon_phone.png` | 56x56 | Displayed at 20x20 in the signature. |
| `icon_web.png` | 56x56 | Displayed at 20x20 in the signature. |

Do not re-encode, compress, resize or convert these files. Email clients reference them
by URL, and re-encoding the GIF risks breaking the first-frame fallback.

`.nojekyll` disables Jekyll processing so files are served verbatim.
