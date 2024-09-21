# dummy-go-app

A dummy app doing nothing that I can use for slsa trials

## SLSA

This repository has 2 workflows:

* SLSA generic generator: Which uses the [slsa-github-generator action](https://github.com/slsa-framework/slsa-github-generator) to build a provenance.
* GitHub attest build provenance: Which uses the [Github integrated method](https://docs.github.com/en/actions/security-guides/using-artifact-attestations-to-establish-provenance-for-builds) of building Provenance attestation. Attestations are available [in a GitHub project page](https://github.com/rrey/slsa-playground-app/attestations).
