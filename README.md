# mail-triage

Bulk-archive the noise in your Gmail inbox. No install, no server, no cost. Open it in your browser, sign in with Google, and clear thousands of emails in minutes.

**[→ Open mail-triage](https://dominiceloe.github.io/mail-triage)**

---

## How to Use

1. Click the link above
2. Sign in with your Google account
3. Review your inbox stats
4. Choose which types of email to archive
5. Preview exactly what will be archived — with counts per rule
6. Confirm with the exact number on the button
7. Watch it run in real time

That's it.

---

## How It Works

mail-triage archives emails by removing the INBOX label — the same thing Gmail does when you press "Archive." Emails move to All Mail. **Nothing is ever deleted.**

### Rules (all on by default)

- **Promotions** — Marketing emails, deals, offers
- **Social** — LinkedIn, Twitter, Facebook notifications
- **Updates** — Shipping confirmations, receipts, automated updates
- **Forums** — Mailing lists and group discussions
- **No-reply senders** — Emails from addresses you can't reply to
- **Unsubscribe links** — Emails with a bulk-send header

### Date filter (optional)

Restrict all rules to emails older than a date you choose. Defaults to 1 year ago.

### Advanced options (off by default)

- **CC'd not TO'd** — Emails where you're CC'd but not the primary recipient ⚠️ review carefully
- **Mark as read** — Also mark archived emails as read to clear your unread count

---

## Privacy

**Your emails never leave your browser.**

mail-triage runs entirely in your browser as a static HTML file. It connects directly to Gmail's API using your Google account. No data is sent to any server — not mine, not anyone's. There is no backend, no database, no analytics, no tracking.

The source code is right here. Read it.

---

## What It Doesn't Do

- Never **deletes** anything — archive only, always reversible
- Never sends your data anywhere — no server, no backend
- Doesn't require any accounts, subscriptions, or API keys from you

---

## Running Locally (Optional)

If you'd prefer to run it from your own machine instead of the hosted version:

1. Download `index.html` from this repo
2. Serve it locally:
   ```bash
   python3 -m http.server 8080
   ```
3. Open `http://localhost:8080` in Chrome

---

## Phase 2 (Coming Soon)

AI-powered reply drafting — smart responses for the emails that actually need your attention, after the noise is gone.

---