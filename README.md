# One AI Cost Portal — login page

Sign-in page for the One AI Cost Portal (Group AI Technology, CDAIO Office).

- `index.html` is self-contained: inline CSS and JS, fonts from Google Fonts.
- **Sign in with Microsoft** links to `/auth/login`. Point that at your Entra ID / OIDC start route.
- Query parameters: `?signedout=1` shows a signed-out notice, `?error=access_denied` an access message, any other `?error=` a generic retry message.
- Corner logo: place the Absa mark at `logos/absa.svg`; until then a text ring is shown.
- The animated mark honours `prefers-reduced-motion`.
