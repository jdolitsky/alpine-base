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
| `migration` `migration-20221129` | `sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221123` | `sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221125` | `sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7179e40aca2bf269984e015c47f932e0ac9746fc33a70ad1ad5a86850c71530d) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221126` | `sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221127` | `sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221128` | `sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `latest` | `sha256:78e75efbbcd94aa1e1ccaf0fb9b6f1633bf66dd5f883fae4e7514b11cf0c8fbf`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:78e75efbbcd94aa1e1ccaf0fb9b6f1633bf66dd5f883fae4e7514b11cf0c8fbf) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221120` | `sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221121` | `sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221124` | `sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |


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
        "docker-manifest-digest": "sha256:78e75efbbcd94aa1e1ccaf0fb9b6f1633bf66dd5f883fae4e7514b11cf0c8fbf"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "c8d8aab637e3451be0dbc52daae12463288de318",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIQCIjLs+uIlFP7Fs/eDz/gUvfGl4/5FZXgFpnxjE4kWodgIgdZPjQU+FawvljEMgUBg0A8FlFiu5W0Kf2UhRaTLcw0w=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiJlZDNiMGJhM2I5ZWMyYjM3MzA3ZTNlMzliMWQwMzU5NmQxZGFmMTM1NmI0MzFmN2E3MTg5NTM1OWI3OTc5Y2Q2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FWUNJUUNnUnluYWo0b3ExZWRCZjRUS3VBTTVoM3l3eGgwZkNONGRFRnVqeEhZRDl3SWhBUDNSVDBJUG1iZjMwcjZFOWs5OWsrZmlnK2dqdXc3ZFlKcFgvVnF4MmNSbCIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjBWRU5EUVhwNVowRjNTVUpCWjBsVlZrUkNaM1ZzU2psa1RFOHhTek5GT0c1eVNVMVdXVU00VFZoRmQwTm5XVWxMYjFwSmVtb3dSVUYzVFhjS1RucEZWazFDVFVkQk1WVkZRMmhOVFdNeWJHNWpNMUoyWTIxVmRWcEhWakpOVWpSM1NFRlpSRlpSVVVSRmVGWjZZVmRrZW1SSE9YbGFVekZ3WW01U2JBcGpiVEZzV2tkc2FHUkhWWGRJYUdOT1RXcEplRTFxUVRGTlZHTjRUbXBWTVZkb1kwNU5ha2w0VFdwQk1VMVVZM2xPYWxVeFYycEJRVTFHYTNkRmQxbElDa3R2V2tsNmFqQkRRVkZaU1V0dldrbDZhakJFUVZGalJGRm5RVVYwY1dSRFdWRm1lV2xDZG1wMVpUbDZUMFpaUldjeWRYZzRWVlZyVjJOM0wweHJlREFLU0VrME5uUXdZV05ZVm1WdlJIZFVVWFJwUkdwR1IyUXJWVmgzTlhkd1QyUkZXalZQVUVoWk1rMUVVbVJIZDBOamFUWlBRMEZzYzNkblowcFlUVUUwUndwQk1WVmtSSGRGUWk5M1VVVkJkMGxJWjBSQlZFSm5UbFpJVTFWRlJFUkJTMEpuWjNKQ1owVkdRbEZqUkVGNlFXUkNaMDVXU0ZFMFJVWm5VVlZJVjNCUENtWlNlbEZsVkdkdWFrdElja3BSY2tSd1Z6bHZVM0kwZDBoM1dVUldVakJxUWtKbmQwWnZRVlV6T1ZCd2VqRlphMFZhWWpWeFRtcHdTMFpYYVhocE5Ga0tXa1E0ZDJGQldVUldVakJTUVZGSUwwSkdOSGRZU1ZwaFlVaFNNR05JVFRaTWVUbHVZVmhTYjJSWFNYVlpNamwwVERKT2IxbFhiSFZhTTFab1kyMVJkQXBoVnpGb1dqSldla3d5YkhSWlYyUnNZM2s0ZFZveWJEQmhTRlpwVEROa2RtTnRkRzFpUnprelkzazVlVnBYZUd4WldFNXNURzVzYUdKWGVFRmpiVlp0Q21ONU9XOWFWMFpyWTNrNWRGbFhiSFZOUkd0SFEybHpSMEZSVVVKbk56aDNRVkZGUlVzeWFEQmtTRUo2VDJrNGRtUkhPWEphVnpSMVdWZE9NR0ZYT1hVS1kzazFibUZZVW05a1Ywb3hZekpXZVZreU9YVmtSMVoxWkVNMWFtSXlNSGRGWjFsTFMzZFpRa0pCUjBSMmVrRkNRV2RSUldOSVZucGhSRUV5UW1kdmNncENaMFZGUVZsUEwwMUJSVVJDUTJocVQwZFJORmxYUm1sT2FrMHpXbFJOTUU1VVJtbGFWRUpyV1cxTk1VMXRVbWhaVjFWNFRXcFJNazE2U1RSUFIxSnNDazE2UlRSTlEzZEhRMmx6UjBGUlVVSm5OemgzUVZGUlJVaHBOVzVoV0ZKdlpGZEpkbVF5T1hsaE1scHpZak5rZWt3elNteGlSMVpvWXpKVmRXVlhSblFLWWtSQmJVSm5iM0pDWjBWRlFWbFBMMDFCUlVaQ1FtaHFZVWRHY0dKdFpERlpXRXByVEZkc2RGbFhaR3hqZVRsd1lsZEdibHBZVFhkSVVWbExTM2RaUWdwQ1FVZEVkbnBCUWtKblVWQmpiVlp0WTNrNWIxcFhSbXRqZVRsMFdWZHNkVTFKUjBwQ1oyOXlRbWRGUlVGa1dqVkJaMUZEUWtoelJXVlJRak5CU0ZWQkNqTlVNSGRoYzJKSVJWUktha2RTTkdOdFYyTXpRWEZLUzFoeWFtVlFTek12YURSd2VXZERPSEEzYnpSQlFVRkhSVFF3Y0hFeFFVRkJRa0ZOUVZKcVFrVUtRV2xCYmxoTE1YcFhiaTlHZFRsdlQyTlNRWEZxWnpSU1pDOUNPVXRPVDJOMFRUUjJXRlF3VVZoUFREUlZkMGxuV0VOR01WUTBPVGRUY0ROaU1VOVVjZ3BuZDBscFF6ZHFhV054VVc5Q2RqRk5TVWd6ZEU4clVIQm9kbXQzUTJkWlNVdHZXa2w2YWpCRlFYZE5SRnAzUVhkYVFVbDNablZQTmpBM1YyUkVOV05rQ2xGVGRUTmtaWFJMVGpCeFZIQmxMM0IyVVRRME1VNHdiakZXVWtKS1VDdHhObVF6V0U1dk9IWnlORVZRWVV0UWFFeFhWMHRCYWtJM2JFNUNVMjlTYVVFS1ZqRjRjbEJOVjNOSFJUUnRVRTQ1WmxSRVp6WlVTVzlsZERCYVVHOW9PRFkzT1d4M01FUlhRVTlCYUZseFVsVmxNVVpuTVZCa1JUMEtMUzB0TFMxRlRrUWdRMFZTVkVsR1NVTkJWRVV0TFMwdExRbz0ifX19fQ==",
          "integratedTime": 1670260638,
          "logIndex": 8470234,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "c8d8aab637e3451be0dbc52daae12463288de318",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3622372873",
      "sha": "c8d8aab637e3451be0dbc52daae12463288de318"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

