# One AI Cost Portal — login page

Sign-in page for the One AI Cost Portal (Group AI Technology, CDAIO Office).

- `index.html` is self-contained: inline CSS and JS, fonts from Google Fonts.
- **Sign in with Microsoft** links to `/auth/login`. Point that at your Entra ID / OIDC start route.
- Query parameters: `?signedout=1` shows a signed-out notice, `?error=access_denied` an access message, any other `?error=` a generic retry message.
- Corner logo: place the Absa mark at `logos/absa.svg`; until then a text ring is shown.
- The animated mark honours `prefers-reduced-motion`.

## Portal

- `executive.html` is the One AI Cost Portal (sidebar layout): Executive view with total spend, month-end projection and platform cards, plus Operational, Aggregate costs, Individuals & projects, and admin screens.
- Self-contained: inline CSS, JS and illustrative sample data. Replace the `RECS` array with real cost rows (`user, cluster, cat, project, env, month, cost, tokens`) to wire it up.
