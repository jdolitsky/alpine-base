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
| `latest` | `sha256:018367d9372e19d71d87fd2fabf6881f80d7e233fc4c94fcc328a2a3183225d1`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:018367d9372e19d71d87fd2fabf6881f80d7e233fc4c94fcc328a2a3183225d1) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221120` | `sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221121` | `sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221123` | `sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221125` | `sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221119` | `sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration` `migration-20221129` | `sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221124` | `sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221126` | `sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221127` | `sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221128` | `sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
Verification for cgr.dev/chainguard/alpine-base:latest --
The following checks were performed on each of these signatures:
  - The cosign claims were validated
  - Existence of the claims in the transparency log was verified offline
  - Any certificates were verified against the Fulcio roots.
[
  {
    "critical": {
      "identity": {
        "docker-reference": "ghcr.io/chainguard-images/alpine-base"
      },
      "image": {
        "docker-manifest-digest": "sha256:018367d9372e19d71d87fd2fabf6881f80d7e233fc4c94fcc328a2a3183225d1"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "schedule",
      "1.3.6.1.4.1.57264.1.3": "baa0d0e904d9572f22d482f4c1b3992246fd2604",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEYCIQCKfvMJrqjNQdFvB4GGvVYLwWaL+SM9CJWhH9Ly6JpyYQIhAJaSO5NkGM/XcVweufpH/IPYQnQaFKj3S0y8JjnVWd50",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiI2ZGJjZWQwODU0ZDVjYWMxM2E2NzczYzgxYzgxN2QwZjRkYjViNzNiOGRjNzA1OWI4MGQ5NjhiM2MzMjMxOGNiIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUURLbC9VMkxFTEtUdjdUUXRRWDlNdDI3VFRFaHNZb2tTY0p1cEg5dGVBQmh3SWdWYzBwZUh1c3ptMEVFYkdJRFE1ZGpvNG8wL1c4TVNjMUNxUlRjdXcraEswPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjJWRU5EUVRCTFowRjNTVUpCWjBsVlVsWlpTRmh1WVVSbVFVTnlTSFZ6V1RnNE5tZEVSelZyYzNSdmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcE5kMDFxUVRCTlJFRjRUVVJCZVZkb1kwNU5hazEzVFdwQk1FMUVRWGxOUkVGNVYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZ0YkRaQmNsSlFhMmx1ZGxsSU9WbEdVVUpzVGxKVVdHOVdjMlV6VHl0VVZGTm5SMFFLZW5kNlRVNVNiRXRvYm1kMFpFSllOVXA2ZWtSdFJHVnlWVGxtY2tKcU9VRklWRlJVVm10S1FXWmhSM2M1S3pCV2VXRlBRMEZ0UlhkblowcGtUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZIUkVKWkNqRkdiWFJNYTJWa01FMVZaa1JFYm1sMFVEbEdkM0JWZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRHWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSU1dNeVRtOWFWMUl4WWtkVmR3cE9aMWxMUzNkWlFrSkJSMFIyZWtGQ1FYZFJiMWx0Um1oTlIxRjNXbFJyZDA1SFVUVk9WR041V21wSmVWcEVVVFJOYlZrd1dYcEdhVTE2YXpWTmFra3dDazV0V210TmFsbDNUa1JCYzBKbmIzSkNaMFZGUVZsUEwwMUJSVVZDUWpSMVdqSnNNR0ZJVm1sTU0yUjJZMjEwYldKSE9UTmplVGw1V2xkNGJGbFlUbXdLVEc1c2FHSlhkM2RLWjFsTFMzZFpRa0pCUjBSMmVrRkNRbEZSV1ZreWFHaGhWelZ1WkZkR2VWcERNWEJpVjBadVdsaE5kbUZYTVdoYU1sWjZUVUl3UndwRGFYTkhRVkZSUW1jM09IZEJVVmxGUkROS2JGcHVUWFpoUjFab1draE5kbUpYUm5CaWFrTkNhWGRaUzB0M1dVSkNRVWhYWlZGSlJVRm5VamxDU0hOQkNtVlJRak5CVGpBNVRVZHlSM2g0UlhsWmVHdGxTRXBzYms1M1MybFRiRFkwTTJwNWRDODBaVXRqYjBGMlMyVTJUMEZCUVVKb2FHNURUVWhCUVVGQlVVUUtRVVZuZDFKblNXaEJUVXBCUVZkMVIxUkdUbmxPVlU1TmNUQkZZbWhyUmpoTFVrWkhlVE5yWkdST01XeE5TV3RtTmpjd1IwRnBSVUZzTVRCeEsxaGtkUW92VDFGSWMwMVNZM1pTUjFBMGFYcDFSRGxqTTFWeldVUlJVVGsyTDNocGFqRlJXWGREWjFsSlMyOWFTWHBxTUVWQmQwMUVZVkZCZDFwblNYaEJTVEZyQ20xaFFURjJXV3BQVUNzM2FtUnFRemR5WVZjeWRqTmlNME01VVROVWFUaHZkM0l2WVdOM2RFaDFkM3BvWWk5SGJWZE9lbmhhWVRGUmFsTTNZekZSU1hnS1FVcE9TakJhVGxwS09VaHBkMU5PYTJsbmEzZHRTSEIxWVZCRVp6bFVZMGxPTURCblVXSnFNRlJUTHpWNVZUVlNPVlpQV1RCcGRqZDFTamMyV0hJMU1RcHRVVDA5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1675469422,
          "logIndex": 12576825,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "baa0d0e904d9572f22d482f4c1b3992246fd2604",
      "githubWorkflowTrigger": "schedule",
      "run_attempt": "1",
      "run_id": "4088899132",
      "sha": "baa0d0e904d9572f22d482f4c1b3992246fd2604"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

