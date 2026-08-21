# HostDeFi — see `hostdefi`

This repository is a duplicate. The API Evangelist record for HostDeFi lives at
**[api-evangelist/hostdefi](https://github.com/api-evangelist/hostdefi)**, and that is the
one the catalog reads.

There is no profile, no `apis.yml` and no rating here. This repository is kept only
so that inbound links to this URL do not dangle.

## Why there were two

HostDeFi submitted through the [apis.io Add-API form](https://apis.io/add/) more than
once, under more than one name. The intake gate slugs a submission from the **product
name the submitter typed**, while API Evangelist slugs a provider from the **domain it
is served on** — `hostdefi.com` — so the gate created a repository under a slug the catalog
would never look up.

That is a defect in our intake, not something HostDeFi did wrong. The two are reconciled
in `network/_data/renamed.yml`, which maps this slug to `hostdefi` so that submission
notices, S3 records and archive tooling all resolve to the surviving record instead of
reporting it missing.

## If you are from HostDeFi

Nothing is required of you. Your listing is at
[api-evangelist/hostdefi](https://github.com/api-evangelist/hostdefi) and on
[apis.io](https://apis.io/providers/hostdefi/) once the next catalog build runs. If
anything there is wrong, write to kin@apievangelist.com and it gets fixed.

— Kin Lane, API Evangelist · 2026-08-21
