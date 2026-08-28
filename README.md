# image-hosting

Public evidence-image repository for open-source contribution screenshots.

## 用途 / Purpose

This repository hosts **public verification screenshots only** — CLI
integration test output, terminal evidence, and behavior captures that are
embedded in pull requests of public open-source repositories, such as
[DingTalk-Real-AI/dingtalk-workspace-cli](https://github.com/DingTalk-Real-AI/dingtalk-workspace-cli).

Images are referenced in PR bodies as
`https://raw.githubusercontent.com/xlb1130/image-hosting/main/dws-pr-evidence/<repo-owner>/<repo-name>/<branch-or-pr>/<image>.png`
and are uploaded only after byte, URL, and MIME verification.

## 敏感信息禁令 / Sensitive Information Policy

Everything pushed here is **public on the internet**. Treat every upload as
a public disclosure. Before uploading, each image must be reviewed and must
not contain any of the following:

- credentials of any kind: tokens, cookies, API keys, passwords, private
  keys, one-time codes, or authorization headers;
- personal data: real names, phone numbers, email addresses, employee IDs,
  avatars, or other personally identifying information;
- internal infrastructure: intranet hostnames, IP addresses, VPN endpoints,
  internal system names, or internal identifiers;
- employer-internal context: internal repository URLs, internal
  issue/tracker IDs, internal screenshots, or any confidential business
  information.

If an image cannot be fully desensitized (deterministic masking, cropping,
or pixelation), it must not be uploaded here — keep it local and share it
through a private channel instead.

## Maintenance

- Evidence images are organized per source repository and per branch/PR
  under `dws-pr-evidence/`.
- Do not delete or rewrite images that are still referenced by open or
  merged PR bodies; those URLs are part of the public review record.
