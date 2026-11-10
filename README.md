# Labor-Bingo

Concept page for the Alphadent Founders Associate Challenge (Hamzauddin Siddiqui, November 2026).
Not an official Alphadent GmbH page. At launch it would move to alphadent.io/bingo.

## What it does
- Phone-first, tickable 4×4 Labor-Bingo (joker pre-ticked, row/column/diagonal detection).
- Reads the team code from the printed QR code (`?t=H-01` … `?t=H-45`, `?t=P-01` … `?t=P-80`), so every reply traces back to one practice.
- Form: request one test case, or just say which square annoys the team most.
- Submitting opens the visitor's email app with a pre-filled message to info@alphadent.io. The page stores nothing on a server and sets no cookies; ticks are kept only in the visitor's own browser.
- Optional: set `FORM_ENDPOINT` in `index.html` to a form backend owned by Alphadent (e.g. Tally or Formspree) to submit directly instead.

## Publish on GitHub Pages
1. Create a public repository named `labor-bingo` under the `hamzauddin-siddiqui` account.
2. Add `index.html` (and this README) to the root of the `main` branch.
3. Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
4. After a minute the page is live at https://hamzauddin-siddiqui.github.io/labor-bingo/ — the URL every printed QR code points to.
5. Test one code on your phone: https://hamzauddin-siddiqui.github.io/labor-bingo/?t=H-01
