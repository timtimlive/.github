# Contributing to TimTim.Live open source

Thank you for wanting to help. These projects are a **Developer Preview**, so feedback about what is confusing is just as useful as code.

## Before you start

- Read the [Code of Conduct](CODE_OF_CONDUCT.md). It applies everywhere here.
- Security problems go **privately** through "Report a vulnerability" on the Security tab — see [SECURITY.md](SECURITY.md).
- For a bigger change, open an issue first so we can agree on the idea before you spend time on it.

## The API contract comes first

Everything here follows one file: the TimTim.Live API contract, https://timtim.live/partner-api/openapi.yaml.

- Code may only use endpoints, parameters and fields that the contract has.
- Copies of the contract in these repositories are **published from TimTim.Live's source of truth**. Do not edit them by hand. To ask for a change to the API itself, open an issue in [timtim-openapi](https://github.com/timtimlive/timtim-openapi).

## Making a change

1. Fork the repository and create a branch in your fork.
2. Follow the repository's README to install, build and test.
3. Add or update tests. A test should fail if the thing it checks is broken — try breaking it once to be sure.
4. Keep the words simple. If an eight-year-old could not follow a step, rewrite the step.
5. Open a pull request and fill in the template.

## Rules that keep people safe

- Never commit a key, token, password or real customer data. Use placeholders like `tt_test_YOUR_KEY`.
- Event data is untrusted text: show it with `textContent` (or React's normal escaping), never `innerHTML`.
- Only `https:` links and images.
- Server keys (`tt_sk_live_…`) never go in browser code or URLs.

## License

By contributing, you agree that your contribution is licensed under the MIT License of the repository you contribute to.
