# alpine-base

<!---
Note: Do NOT edit directly, this file was generated using https://github.com/chainguard-images/readme-generator
-->

[![CI status](https://github.com/jdolitsky/alpine-base/actions/workflows/release.yaml/badge.svg)](https://github.com/jdolitsky/alpine-base/actions/workflows/release.yaml)

Alpine base image built with [apko](https://github.com/chainguard-dev/apko). Uses packages from the [Alpine distribution](https://www.alpinelinux.org/).

## Get It!

The image is available on `cgr.dev`:

```
docker pull cgr.dev/chainguard/alpine-base:latest
```

## Supported tags

| Tag | Digest | Arch |
| --- | ------ | ---- |
| `migration-20221119` | `sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221123` | `sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221128` | `sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221126` | `sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221127` | `sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `latest` | `sha256:d62f2cd7c5e3c63088058b5c37898eeef9e7f6fcb1955be3dd29402716045fe4`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d62f2cd7c5e3c63088058b5c37898eeef9e7f6fcb1955be3dd29402716045fe4) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration` `migration-20221129` | `sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221120` | `sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221121` | `sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221124` | `sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221125` | `sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


## Usage

```
docker run cgr.dev/chainguard/alpine-base echo "hello"
```

See the [examples/](./examples/) directory for how
to use this as a base image.


## Signing

All Chainguard Images are signed using [Sigstore](https://sigstore.dev)!

<details>
<br/>
To verify the image, download <a href="https://github.com/sigstore/cosign">cosign</a> and run:

```
COSIGN_EXPERIMENTAL=1 cosign verify cgr.dev/chainguard/alpine-base:latest | jq
```

Output:
```
Error: --certificate-identity or --certificate-identity-regexp is required for verification in keyless mode
main.go:74: error during command execution: --certificate-identity or --certificate-identity-regexp is required for verification in keyless mode
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

