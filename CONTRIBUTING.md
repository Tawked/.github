# Contributing to Tawked's SDKs

These repositories are read-only mirrors. Each SDK is developed in Tawked's own repository beside the API it calls, and every release is published here from there.

## Issues are welcome

Open an issue for a bug, a wrong or unclear doc, a missing feature, or a runtime or version where the package fails. Search the open and closed issues first.

Please include:

- the package and its version;
- your runtime and its version (Node.js, Bun, Deno, PHP, Laravel, Python, Better Auth);
- the request id (`X-Request-Id`) of a failing call, if there is one;
- the smallest code that shows the problem.

Never paste an API key, an account token or a webhook secret. Remove them before you post.

## Pull requests

A pull request is read as a proposal. We cannot merge it here; if we take the change, we make it in our repository, credit you as a co-author, and it reaches this repository with the next release. Small fixes to docs and examples are easiest to take. Most code is generated from the API's contract, so a change to a generated file is made in the generator.

## Running the tests

Each repository runs its own CI (`.github/workflows/ci.yml`) on pull requests and on pushes to `main`: the install, the type checks (and the linters where the repository has them), and the tests that need nothing outside the repository. The npm and Python packages also build and check what they will publish. The steps of that file are the commands to run the same checks on your machine.

The tests that call a local stand-in for the API and compare the package with the API's contract need files that are not in this mirror, so they run in our repository before every release.

## Questions about your integration

Questions about your account, your keys or how to build something are not issues. Read the docs at [docs.tawked.com](https://docs.tawked.com) or write to support@tawked.com.
