# Admin (deprecated)

This repo held an early standalone prototype of the EchoImpact admin
panel (`admin.html`). It has been superseded by the fully-featured admin
panel built into the main site — see `src/Admin.jsx` in the `gunners`
repo, served at `/admin`.

`admin.html` still pointed at the live production Supabase project and
login API while carrying only a fraction of the current feature set and
drifted field names, making it a stale, unaudited second surface against
production. It has been replaced with a static notice and no longer
calls the API.
