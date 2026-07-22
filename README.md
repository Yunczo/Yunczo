# Yunczo

I build small, inspectable tools with clear privacy and delivery boundaries.

## Available now: CI Rescue

One failing GitHub Actions workflow, one focused diagnosis, and one reviewable patch.

- **US$49 equivalent in Bitcoin**
- Scope response normally within 24 hours
- Delivery within 48 hours after confirmed payment and sanitized inputs
- No login or email; payment is requested only after written scope acceptance
- Public synthetic proof, runnable CI verification, and no invented client claims

[Send an encrypted scope request](https://yunczo.github.io/ci-rescue-service/#anonymous-intake) · [View the service](https://yunczo.github.io/ci-rescue-service/) · [Inspect the proof run](https://github.com/Yunczo/ci-rescue-service/actions/workflows/public-proof.yml)

No security or vulnerability work, credential handling, production access, or private data is accepted through public issues.

## Free diagnostic Action

Run the offline, read-only diagnostic against one workflow and an optional saved, sanitized log:

```yaml
- uses: Yunczo/ci-rescue-service@v1
  with:
    workflow-path: .github/workflows/ci.yml
    fail-on: none
```

The Action writes a Markdown report and job summary, makes no network requests, and does not edit the inspected files. [Release v1.0.1](https://github.com/Yunczo/ci-rescue-service/releases/tag/v1.0.1) is verified across Ubuntu, macOS, and Windows.

## Free local toolkit

[CI Rescue Kit 1.0.0](https://github.com/Yunczo/ci-rescue-service/releases/tag/toolkit-v1.0.0) is the MIT-licensed offline diagnostic used for the public examples. Its published checksum and full test run are independently inspectable.

If it saved you time, [optional Bitcoin support](https://github.com/Yunczo/ci-rescue-service/blob/main/SUPPORT.md) helps maintain it. Support is not a service purchase.
