# Security policy

## Supported versions

Security fixes land in the newest release of each package. Before 1.0 that is the newest 0.x minor.

| Package | Registry | Supported |
|---|---|---|
| `@tawked/sdk` | npm | latest 0.x |
| `@tawked/better-auth` | npm | latest 0.x |
| `tawked/tawked-php` | Packagist | latest 0.x |
| `tawked/laravel` | Packagist | latest 0.x |
| `tawked` | PyPI | latest 0.x |

## Reporting a vulnerability

Do not open a public issue. Report it privately through GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability) (the **Report a vulnerability** button on the repository's **Security** tab), or by email to support@tawked.com with "Security" in the subject.

Please include:

- the package and its version;
- what an attacker could do, and to whom;
- the steps to reproduce it, or a short proof of concept.

Never send a real API key, account token or customer data. Use a test key, or replace the value with `tk_test_...`.

## What happens next

We reply to every report, keep you informed while we work on a fix, and credit you in the release notes unless you ask us not to.

## Scope

The five SDK packages above and their repositories in the [tawked](https://github.com/tawked) organization. Vulnerabilities in tawked.com, the console or the API are reported the same way, to the same address.
