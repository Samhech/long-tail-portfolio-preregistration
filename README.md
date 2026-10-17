# long-tail-portfolio: pre-registration timestamps

This repository holds **only SHA-256 fingerprints**. The research project itself is kept private.

## What this proves

I test whether a bank gains by adding a sleeve of niche funds (low demand one by one, significant together) to a core exposed to AI, with shared liquidity logistics: the *Amazon vs Walmart* idea applied to finance, here on real private-credit funds (2023-2026).

Before running any test, I wrote down the rules, froze the data and the code, and recorded their fingerprints here. A fingerprint changes completely if a single character of the file changes. Anyone can later recompute the fingerprint of a file I share and check that it matches the one published here, at the date shown by GitHub.

How to check a file: `shasum -a 256 <file>` (macOS/Linux) or `Get-FileHash <file> -Algorithm SHA256` (Windows).

Private repository snapshot: commit `fa42baa550ee5e69fae624fa2ae14cbdee2051d9`.

## Pre-registration texts and audit trail

| File | Content | SHA-256 |
|---|---|---|
| `rapport/preenregistrement_h17_h18.md` | Pre-registration of H17 and H18 (validated 14 Oct 2026) | `5bc5f346f180b2b2383908d0f7cccfe197e4e330add239b5ed065b9f2a34e902` |
| `rapport/specification_h17_h18.md` | Code specification | `31111aac34236cf95ac752313e8c6ada3ab46cdac8c540a42ff33e75f26341d1` |
| `rapport/protocole_validation.md` | Full protocol, with dated amendments (sections 13-15) | `600dc209b44c4cc1d59deedacf33ba5c1f56fbbe4aa10f28f5f2c74b2e8e5ec1` |
| `rapport/journal_des_essais.csv` | Trial journal (every decision and run, dated) | `fd714a4577e9f3697dfc62f085d729448f5d81ff2108f83e920854c2bab2d039` |

## Frozen data (public SEC EDGAR filings, frozen 14 Oct 2026)

| File | Content | SHA-256 |
|---|---|---|
| `data/credit_prive_panel_h17_h18.csv` | Panel: 65 private-credit funds, 2021Q4-2026Q3 | `4654eb01ef543ba661512ac74991970c6e7df21bb50d0ecf75a1680acf5a3cde` |
| `data/credit_prive_panel.csv` | Earlier frozen panel (step 16) | `460098493740acb1891de5b4b58c2f17565600d3e9274dc60ea7e534bc7277f9` |
| `data/credit_prive_fonds.csv` | Frozen fund list | `0138b53008988513466b081a6b1b654b14739f62ff4c2990319ec8b96918ca99` |
| `data/etape17_18_variables.csv` | Fund families and sponsors | `78248722ce4b68e42f8e1e0b7b2ccfe32e9319b0568ab9d9d66f424f1fc31352` |
| `data/etape17_18_formes.csv` | First offer and legal form | `b876e39fc6e53a4ecfed092b92acde8a3ff13c163e31f6bdeb55d262b1b998d7` |
| `data/etape17_18_exclusions.csv` | Exclusions | `4a7f0567f3dc21b8ac1538ffa8a63f9f8becc72a80967906e9063547e04315ac` |
| `data/etape17_18_releves/souscriptions_calendaires.csv` | Calendar-quarter subscriptions | `a6aecc631a3b65c8a6ce618e5e88d1d5e0e53e40bcc018b4db11139ea42c1033` |
| `data/etape17_18_releves/d1_cellules.csv` | Cells added before the freeze | `d59fbc17a38227f9aca2b3fdae3db9cd89a157e45de8f2ebfeb51319f1cb8a8f` |
| `data/etape17_18_releves/revisions.csv` | Revisions found | `d5574072a940a2bb6a09ae4f7a7630ecffbf0350bfbf559099f1f7fe691466af` |
| `data/exposition_logiciels_h18.csv` | Software exposure at 31 Dec 2025 | `4a9a8becdaf79f795dd5cfe7866c23b2f31ae032ec62dd439453f7cd37e5ca15` |
| `data/h17_entrees_externes.csv` | External inputs (fees, caps) | `dc65a23727b1bad60366c89f00e6dfc35a14696459a40717c48645fe362cdeb2` |
| `data/h17_conformite_12d1-4.csv` | Rule 12d1-4 check | `7d20e0b598482a488ad856f87bf4675c109cfb5109cef737cdf9ce77105ed7ef` |
| `data/etape17_18_niches_ia.csv` | AI-linked niche classification | `2e75d234e38dfd0ef7bf1699db7e084b85aa4637e8b224a6878c667a9075dadb` |

## Code (fingerprints recorded by the dry run)

| File | Content | SHA-256 |
|---|---|---|
| `R/credit_prive_h1718.R` | H17/H18 tests | `7c03133ed1e96666dd683e2338e2ee8dd0af9b64c7643858dafe01bb46b51044` |
| `scripts/17_18_preparation.R` | Structures | `9bb6949ebe4ae9f6642276e7fd81e77535cb30ae7ec6666899f7e2f2fb316f6a` |
| `scripts/17_18_blanc.R` | Dry run on a fictitious panel | `5f8f76f7e3361efe6446c37fbf101c599389a33fd267334973211bc3d7b831a2` |
| `scripts/17_18_lancement.R` | Single launch | `9e5ddb9af4211c96398a346df7011dfb3010626b47df0627270eb11d9b9942d9` |
| `tests/test_h1718.R` | Unit tests | `fe668f9dc9ac4175544e72487e22b46e300a15b878b3389f4a9e228a094b42c6` |
| `R/credit_prive.R` | Step 16 code | `7ebf03944c6d667226470df73968d1848ac6ad3682b8c3de159ce75721239ed8` |
| `R/logistique.R` | Step 16 code | `6c2b3dcbacca9b1fb63828b788f02df0c0109258272685e98ccbd5fa8b9525fe` |
| `R/validation.R` | Step 16 code | `f0fc435a1f0ebd2ffbcd664c7bfa754f3e3a136bba3860042be8ba37be5c7dfd` |
| `scripts/16_entrepot_credit_prive.R` | Step 16 launch | `44ff004a5615bbce5620a15ff6332f8b539b8f1f6a9df6ccc75e1262caa8cea4` |
| `scripts/16b_previsions_4T2026.R` | Step 16 dated forecasts | `c3e3a038566ac4f7e28d50c29ecb67e3da6b607eb0dfd60d2e6b443c95ff5b46` |

## Test structures and dry run

| File | Content | SHA-256 |
|---|---|---|
| `resultats/h1718_structures.csv` | Which funds enter each test (no values) | `c9768642444ff24dd2c5408637173bc1924045020dcee95f3fe43ad971a354ca` |
| `data/credit_prive_panel_h17_h18_fictif.csv` | Fictitious panel used for the dry run | `232f82de22a3f0f3c488e8a94a989f953d6105bc7fe68b898a0795cd440497ba` |

## Dated forecasts (added on the launch day, before any outcome is known)

- H17/H18: share of fresh money going to niche funds in Q4 2026 (`resultats/h1718_prediction_4T2026.csv`). Fingerprint added on the launch day.
- Step 16: Q4 2026 redemption requests of 7 funds (`resultats/etape16_previsions_4T2026.csv`). Fingerprint added by 15 November 2026.
- The forecasts are scored in 2027, once the Q4 2026 filings are public; the files are published with the score.
(https://github.com/Samhech/long-tail-portfolio-preregistration/edit/main/README.md)](https://github.com/Samhech/long-tail-portfolio-preregistration/edit/main/README.md)](https://github.com/Samhech/long-tail-portfolio-preregistration/edit/main/README.md)
