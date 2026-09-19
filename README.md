# RallyLog public site

Public holding site for **RallyLog**.

This repository is intentionally separate from the frozen RallyLog application and internal product documentation. It will serve `rallylog.ai` through GitHub Pages while the preserved prototype remains available at:

`https://rally-log-38d8d026.base44.app`

## Hosting

- GitHub Pages
- Source: `main` branch, repository root
- Custom domain: `rallylog.ai`

## DNS migration rule

Do not change Porkbun DNS until GitHub Pages is enabled and the Pages build has been verified. When the static site is ready, replace only the Base44 apex/`www` routing with the DNS records required by GitHub Pages. Preserve the existing SPF/TXT email record unless email configuration is intentionally handled as a separate task.

## Scope

Public static-site files only. Do not add user data, Base44 exports, private product documents, credentials, secrets, or archived user media.
