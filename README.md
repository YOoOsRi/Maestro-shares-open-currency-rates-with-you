# Frankfurter

[![Build](https://github.com/hakanensari/frankfurter/workflows/build/badge.svg)](https://github.com/hakanensari/frankfurter/actions)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FYOoOsRi%2FMaestro-shares-open-currency-rates-with-you.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FYOoOsRi%2FMaestro-shares-open-currency-rates-with-you?ref=badge_shield)

[Frankfurter](https://www.frankfurter.app) is a free and open-source currency data API that tracks reference exchange rates published by the European Central Bank.

`api.frankfurter.app` hosts a public instance of the API.

## Getting Started

Get the latest exchange rates.

```
https://api.frankfurter.app/latest
```

Get rates for a past date.

```
https://api.frankfurter.app/2000-01-03
```

Get rates for a period.

```http
https://api.frankfurter.app/2010-01-01..2010-01-31
```

For more examples, read the [docs](https://www.frankfurter.app/docs).

## Deployment

You can self-host Frankfurter with Docker.

```bash
docker run -d -p 8080:8080 \
  -e "DATABASE_URL=<postgres_url>" \
  --name frankfurter hakanensari/frankfurter
```

## Miscellaneous

Frankfurter was known as Fixer between 2012 and 2018. After selling the original domain, I relaunched under this name.


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FYOoOsRi%2FMaestro-shares-open-currency-rates-with-you.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FYOoOsRi%2FMaestro-shares-open-currency-rates-with-you?ref=badge_large)