## ATTMS 1.1.0 (build 113) - first public release

**What it is:** the complete Windows package - hub, agent with the Windows and SAP GUI recorders,
web app, bundled Chromium, example cases and the ClaimsHub demo project. Signed; the hub checks every
file at start.

**Install:** unzip, double-click `ATTMS.bat`. Check the download with the `.sha256` file.

**New: Hotfix Shield** - one page per production incident: computed test scope with reasons, red-to-green proof of the fix, signed go/no-go.

**Free Community edition:** no key needed - up to 2 agents and 3 users. A licence key lifts the limits and adds plugins, single sign-on, Hotfix Shield, release sign-off, the compliance pack, monitoring, tracker write-back and CAN hardware adapters.

**In this release:** 34 step types (browser, Windows desktop, SAP GUI, mobile, API, database, Kafka,
MongoDB, S3, files, CAN/UDS/DoIP, k6 load, PDF, reconciliation, plugins); browser, desktop and SAP
recorders; plain-English steps and AI drafts from Jira/Polarion/codeBeamer stories with a local
model; data-driven runs, environments, schedules, CI runner with JUnit; stories, acceptance criteria,
reviews with electronic signatures, sprint board, release cockpit with gates and sign-off, coverage
map for ASPICE/ISO 26262/Solvency II audits; Jira/Zephyr/Azure DevOps/Slack/Teams; roles, LDAP and
OpenID Connect SSO, hash-chained audit log, secrets encrypted at rest, HTTPS, per-agent tokens,
sandboxed plugins, signed in-app updates with rollback, Prometheus metrics, OpenAPI.

**Known limits:** CAN hardware (PCAN, Kvaser, Vector) is validated against simulators and vendor
stand-ins, not yet on a production bench; German UI partly translated.

**Assets:** `ATTMS-1.1.0-build113.zip` and its `.sha256` checksum file.
SHA-256: d250706ca476250fdca5fd00a711638ec0cef46b86abcac858387bb3da9a8921
