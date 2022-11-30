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
| `migration` `migration-20221129` | `sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221123` | `sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221124` | `sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221126` | `sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221127` | `sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `latest` | `sha256:5de96740e48218ac03b9f2f80f5c752b1ef45d97c46126efd028b1e15b5e6f60`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:5de96740e48218ac03b9f2f80f5c752b1ef45d97c46126efd028b1e15b5e6f60) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221119` | `sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221120` | `sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221121` | `sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221125` | `sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
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
        "docker-manifest-digest": "sha256:5de96740e48218ac03b9f2f80f5c752b1ef45d97c46126efd028b1e15b5e6f60"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "5df1c34ec619db5563913c4201e5689378d04702",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIFZe+prWEs9OZtbQjec7iXGRNvK0RBONLRtDoWAn8incAiEAoMXMV/brsx79Bv03HGHU6FaN49iNQ0TkyD/h2H4OcrM=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIwYzM3MzNjMGVlZTlhZWQ4NWIyZTNhMzhiNTBkOTdlYzVlOTk4MjA3ZjJiMWI4M2VmMTJmMGY2N2ExZjVjOWJiIn19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJUUNrdlBBTkU3d1N0dFl0ZUxic3oxdkRvckNnb01jcmhlWXlWRzFzRVZBNGFRSWdlem52OEU3dGw4UHBXUSs3RDI0UDNzK3M4UnI1cWhHcTFGYkhYRnZYK0lVPSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjFSRU5EUVhvMlowRjNTVUpCWjBsVlYweDRhM2xTVFVaV1dWcHNkWFpEVDBwVVQxbFNMMWxwWnlzNGQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFVU1RWTlZFRjZUVlJKTTFkb1kwNU5ha2w0VFZSSk5VMVVRVEJOVkVrelYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVZtVFhVNVRGRlRjRkUwWXpoeU9VaGhRV1pyVUc1NVpXd3lXRTl0YjJGYVNFVjZLM2NLYmxoeVprNUdSRUZoVEZjck5rRnVXQzl3Y1RkQ1JWQlBPR2RSWkc4d2EwNXZlVzEwTTIwdmRuQlFlbE5MYmtoRlJrdFBRMEZzTUhkblowcGFUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlYzVFdWb0NqUlVTMUUyUm1RNVVqZHdNRFpzVkhSYVpYcGFaSE5GZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJjeFdrZFplRmw2VFRCYVYwMHlUVlJzYTFscVZURk9hazAxVFZST2FrNUVTWGROVjFVeFRtcG5OVTE2WXpSYVJFRXdDazU2UVhsTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjB4Q1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtnd1JXVjNRalZCU0dOQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSWGQyUlV3MVowRkJRa0ZOUVZORVFrY0tRV2xGUVdreVMwUXZRM0pDTjFSVlVtaFdlbVZWVjBoS1ZVMW1XRXB2WVdsMVpETlRaRWhJVkZaUVltcHFkVTFEU1ZGRVpqTm5iM0JwTm5WcVIzSmpTd3BqYVdoWVYwSXpjbWh0VVc1aFNHNTJLelpoVDBwWmJ6TTJhV0ZsYVhwQlMwSm5aM0ZvYTJwUFVGRlJSRUYzVG05QlJFSnNRV3BGUVRWR05sSmxLMFJwQ21wQ05YQmljbEpKVjBOelRrTjZVbE5zYnl0WUswWTRWRUkyWWtkMGFHaGtOME51TDNGWlExZzRkM0F5YUc1RGJuRm1ZV2xuYkV3dlFXcEJlWEI2U1dFS1NHUnNaM0I0YUhwNWQwUTVRamxYZWxWRFZGRkxNVTFuTWt3elMyMWFabEExWVc4MGRFMTZlRlEzZUdGQ1FVTlRXWEkyUVd0YVJUVXlPVFE5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1669717921,
          "logIndex": 8079576,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "5df1c34ec619db5563913c4201e5689378d04702",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3573207955",
      "sha": "5df1c34ec619db5563913c4201e5689378d04702"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

