# OwnYourProduct Salon

A beauty salon's whole product under your own name — the product's own front on the
Chatfuel engine: calendar and booking window, clients, services and staff levels, reports
and expenses, five-step set-up, Instagram answered with your prices.

```sh
npx @chatfuel/wizard --app ownyourproduct-salon --apps-repo <this catalog>
```

Modules: `auth` (accounts) and `admin` (the account's workspaces and bots). The product
itself is not an overlay: it is fetched from its own repository by step 1 of the build
plan (it is larger than an overlay may be) and copied into your app, so the whole source
is yours.

See [`playbook.md`](playbook.md) for the build plan your coding agent follows.
