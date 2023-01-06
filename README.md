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
| `migration-20221124` | `sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:a312acfc928436e7069f9fec682691aaa21f46003f69394ba8c6fff78cee8017) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221119` | `sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:b45e881509e4fe79101a62692735840ffad724b9f999cd1d587f386c446bb7e6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration` `migration-20221129` | `sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:ead088bc7969ef1a30cb8af403d58f0c988993edf7280d88ec9aff08d0ca7876) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221120` | `sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:d0bf89ec9e1e7986e76115d112234e05170253276d22169ae802a18de9029401) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221122` | `sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:722945263e52c45b8ca77bb3a3d20edc60797eceaa61d64664b2341682121932) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221126` | `sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:7c668b415a9559b3f343b6ba9e2112ff67b86462a3397f2b26a3aaf6e8a40628) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221127` | `sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:562869007700e8a9cd0c11a6bcba9b850cc9c4e90a229f4cc98874752eb044a6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221128` | `sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:e8e0822438a430fdfea63773067fde1d231aac2327dee7a494ac2b02986c3418) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `latest` | `sha256:bcd6678bdeb3ae9981e8631bb551c440bfc4fa66d7e28a2ed1d359147afa9c1e`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:bcd6678bdeb3ae9981e8631bb551c440bfc4fa66d7e28a2ed1d359147afa9c1e) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221121` | `sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:466083e3e0fbd5808ce39af0989d6cf06cc010433c5fe15f9210c96ab409afe6) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
| `migration-20221123` | `sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8`<br/>[View entry in Rekor](https://rekor.tlog.dev/?hash=sha256:81cbe6508c8c8a13951dfcb27a1a070a1d53cfe945b5ff2312ea2b2176b04ed8) | `386` `amd64` `arm64` `armv6` `armv7` `ppc64le` `riscv64` `s390x` |
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
        "docker-manifest-digest": "sha256:bcd6678bdeb3ae9981e8631bb551c440bfc4fa66d7e28a2ed1d359147afa9c1e"
      },
      "type": "cosign container image signature"
    },
    "optional": {
      "1.3.6.1.4.1.57264.1.1": "https://token.actions.githubusercontent.com",
      "1.3.6.1.4.1.57264.1.2": "push",
      "1.3.6.1.4.1.57264.1.3": "cbb56b39c344605f135f32a4159151fc088e253d",
      "1.3.6.1.4.1.57264.1.4": ".github/workflows/release.yaml",
      "1.3.6.1.4.1.57264.1.5": "chainguard-images/images",
      "1.3.6.1.4.1.57264.1.6": "refs/heads/main",
      "Bundle": {
        "SignedEntryTimestamp": "MEUCIBY347h9+HhBlZo64wk9HFfXpTfJ/dvLUU2TsblZLzPmAiEAi7oP8n16BD64KfbdaixxK+LPvpDDzD28ccUYwN4K2w8=",
        "Payload": {
          "body": "eyJhcGlWZXJzaW9uIjoiMC4wLjEiLCJraW5kIjoiaGFzaGVkcmVrb3JkIiwic3BlYyI6eyJkYXRhIjp7Imhhc2giOnsiYWxnb3JpdGhtIjoic2hhMjU2IiwidmFsdWUiOiIyODQwNTk5ZDhjZmFiYWU2ZDk1NjdkYzBlMzcxYzZmNzJhYTllMzU5N2I3NDRjZTFiNDc1MGNhNWU3MDA0NDQ2In19LCJzaWduYXR1cmUiOnsiY29udGVudCI6Ik1FVUNJRG12cnUrTTVLakVuV2ZjUE1SSlhqYmVkZDlpMmpLV1A2Ujgwb1dBcWkvUkFpRUFtamdSaTJMWGZscCsxRTBET2pFMkswZHVqUlpsejNOa3ZMNnBaTVB6eXQ0PSIsInB1YmxpY0tleSI6eyJjb250ZW50IjoiTFMwdExTMUNSVWRKVGlCRFJWSlVTVVpKUTBGVVJTMHRMUzB0Q2sxSlNVUjBla05EUVhveVowRjNTVUpCWjBsVVUwMXlSakUyVWtkWGJVVTVTbEUzV1dWVVNpdEZRVTF1ZVhwQlMwSm5aM0ZvYTJwUFVGRlJSRUY2UVRNS1RWSlZkMFYzV1VSV1VWRkxSWGQ0ZW1GWFpIcGtSemw1V2xNMWExcFlXWGhJYWtGalFtZE9Wa0pCVFZSR1dFNXdXak5PTUdJelNteE1WMngxWkVkV2VRcGlWMVpyWVZkR01GcFVRV1ZHZHpCNVRYcEJlRTFFVlhoTlJGRXpUWHBHWVVaM01IbE5la0Y0VFVSVmVFMUVWVE5OZWtaaFRVRkJkMWRVUVZSQ1oyTnhDbWhyYWs5UVVVbENRbWRuY1docmFrOVFVVTFDUW5kT1EwRkJWRWRPT0dGdlNIWlFWRWxrYUdOa1NHZEZXSFZKWm5Cb1MwVTBXbGRTTlhoR1ZIWkNORFFLWWs0M1ZXb3JlVEptWmxJNE1IaHVWa1JoTm1sek4zQjFTSEpqZEdocGFVcHRNU3RJZFZSUlNuRXlNa1JNY2pOdWJ6UkpRMWhVUTBOQmJHdDNSR2RaUkFwV1VqQlFRVkZJTDBKQlVVUkJaMlZCVFVKTlIwRXhWV1JLVVZGTlRVRnZSME5EYzBkQlVWVkdRbmROUkUxQ01FZEJNVlZrUkdkUlYwSkNVVXBsTmxBMkNpdEJOWEJwUW5kdGVrcG5WMGxOVVhKcllYSXlWVlJCWmtKblRsWklVMDFGUjBSQlYyZENWR1l3SzI1UVZtbFJVbXgyYlc4eVQydHZWbUZNUjB4b2FHc0tVSHBDYjBKblRsWklVa1ZDUVdZNFJWaHFRbU5vYkhCdlpFaFNkMk42YjNaTU1tUndaRWRvTVZscE5XcGlNakIyV1RKb2FHRlhOVzVrVjBaNVdrTXhjQXBpVjBadVdsaE5kbUZYTVdoYU1sWjZUSGsxYm1GWVVtOWtWMGwyWkRJNWVXRXlXbk5pTTJSNlRETktiR0pIVm1oak1sVjFaVmRHZEdKRlFubGFWMXA2Q2t3eWFHeFpWMUo2VERJeGFHRlhOSGRQVVZsTFMzZFpRa0pCUjBSMmVrRkNRVkZSY21GSVVqQmpTRTAyVEhrNU1HSXlkR3hpYVRWb1dUTlNjR0l5TlhvS1RHMWtjR1JIYURGWmJsWjZXbGhLYW1JeU5UQmFWelV3VEcxT2RtSlVRVk5DWjI5eVFtZEZSVUZaVHk5TlFVVkRRa0ZTZDJSWVRtOU5SRmxIUTJselJ3cEJVVkZDWnpjNGQwRlJUVVZMUjA1cFdXcFZNbGxxVFRWWmVrMHdUa1JaZDA1WFdYaE5lbFp0VFhwS2FFNUVSVEZQVkVVeFRWZGFhazFFWnpSYVZFa3hDazB5VVhkTVFWbExTM2RaUWtKQlIwUjJla0ZDUWtGUlpVeHRaSEJrUjJneFdXazVNMkl6U25KYWJYaDJaRE5OZG1OdFZuTmFWMFo2V2xNMU5WbFhNWE1LVFVOWlIwTnBjMGRCVVZGQ1p6YzRkMEZSVlVWSFIwNXZXVmRzZFZvelZtaGpiVkYwWVZjeGFGb3lWbnBNTW14MFdWZGtiR042UVdSQ1oyOXlRbWRGUlFwQldVOHZUVUZGUjBKQk9YbGFWMXA2VERKb2JGbFhVbnBNTWpGb1lWYzBkMmRaYzBkRGFYTkhRVkZSUWpGdWEwTkNRVWxGWmxGU04wRklhMEZrZDBSa0NsQlVRbkY0YzJOU1RXMU5Xa2hvZVZwYWVtTkRiMnR3WlhWT05EaHlaaXRJYVc1TFFVeDViblZxWjBGQlFWbFhRbWwzZUM5QlFVRkZRWGRDU1UxRldVTUtTVkZEUTJWdU1EZzBNWGQyTVd3dmIxRm1aa0Y2Wm1wV01EWmhOVmhSZURnd1IwMUtjVEZpVDJ0MU4wWmlVVWxvUVVwWlZWSTRSVEpUUlhGcmQwaGpOZ3BXVjNGTFdsRmtTRXROZW0xeFdEUjZVMWt4ZWxadmVIaDVkVEJtVFVGdlIwTkRjVWRUVFRRNVFrRk5SRUV5WjBGTlIxVkRUVVIzUlc5WWN5dFRNemhvQ21OWk1IRXdla05tV2toMmNXVkhhRXhLV1hvck5FeHJlakJsY21OUWVpdHVWMHg0VldSaGJXbHpWVVp1ZURoU1ptbHhhSFF5ZDBsNFFVeFVURzgxVlRVS2NuRllOemhSVXpocmFYVlFMMnMwTlhCa1RrWTFNR1JTUmtKdGJGbDVOemxTU1M5RVNsTTJTV3RVTW5CeFMwNTRUVzl5Tms5aGRtaHRaejA5Q2kwdExTMHRSVTVFSUVORlVsUkpSa2xEUVZSRkxTMHRMUzBLIn19fX0=",
          "integratedTime": 1672915681,
          "logIndex": 10519058,
          "logID": "c0d23d6ad406973f9559f3ba2d1ca01f84147d8ffc5b8445c224f98b9591801d"
        }
      },
      "Issuer": "https://token.actions.githubusercontent.com",
      "Subject": "https://github.com/chainguard-images/images/.github/workflows/release.yaml@refs/heads/main",
      "githubWorkflowName": ".github/workflows/release.yaml",
      "githubWorkflowRef": "refs/heads/main",
      "githubWorkflowRepository": "chainguard-images/images",
      "githubWorkflowSha": "cbb56b39c344605f135f32a4159151fc088e253d",
      "githubWorkflowTrigger": "push",
      "run_attempt": "1",
      "run_id": "3846015378",
      "sha": "cbb56b39c344605f135f32a4159151fc088e253d"
    }
  }
]
```

You can verify that the image was built in Github Actions in this repository from the `Issuer` and `Subject` fields.
</details>

## Build

This image is built with [apko](https://github.com/chainguard-dev/apko).

