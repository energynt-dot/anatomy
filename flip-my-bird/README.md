# Flip My Bird

A tiny tracker for Australians who switch energy retailers to collect sign-up bonuses
(ShopBack, TopCashback, Econnex, retailer credits, referrals).

It answers three questions:

1. **Who am I with, and when can I flip?** Counts down to the end of the minimum stay
   (usually 2–3 months) so you don't lose the bonus.
2. **Which bonuses are still owed?** Tracks each cashback as *not tracked*, *tracked* or *paid*.
3. **Who can I go back to?** Shows when each retailer you've left will treat you as a
   new customer again (often 12 months).

When you tap **I've flipped**, the old deal gets an end date and you add the new one. The form
warns you if you're leaving before the minimum stay or signing back up with a retailer that's
still in its no-return window.

## Running it

It's one file with no build step. Open `index.html` in a browser.

- Opened as a file or from any web host, data is kept in that browser's `localStorage`.
  Use **Download backup** / **Copy backup** and **Restore** to move it between devices.
- Published as a claude.ai Artifact, data saves to the owner's account and syncs across devices.
