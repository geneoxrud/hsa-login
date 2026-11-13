# hsa-login (public)

Sign-in and approval page for the private **Home Services Library** Claude connector. Supabase Auth's
OAuth server sends you here (`consent.html?authorization_id=...`); you sign in and approve or deny.

Contains no secrets: `config.js` holds the Supabase project URL and the *publishable* key, both meant
to be public. The library itself only accepts signed-in requests from the allowed account.
Library: supabase-js 2.118.0 from jsDelivr, pinned with Subresource Integrity.
