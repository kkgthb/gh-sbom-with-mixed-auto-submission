If I forego a manual `dependabot.yml` file and thereby rely on auto-submission, and if I include a mix of coding languages, some of which automatically submit dependencies and others of which don't but are eligible to be SBOM-scanned by GitHub's Dependabot, which coding language's packages actually end up in the SBOM?

* https://docs.github.com/en/code-security/concepts/supply-chain-security/dependency-graph-data#dependabot-graph-jobs
* https://docs.github.com/en/code-security/reference/supply-chain-security/dependency-graph-supported-package-ecosystems#supported-package-ecosystems

I'm hoping to see both NPM's `express` and `shx` as well as GitHub Actions's `actions/checkout` in [this repo's SBOM](https://api.github.com/repos/kkgthb/gh-sbom-with-mixed-auto-submission/dependency-graph/sbom).