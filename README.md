# long-tail-portfolio: pre-registration timestamps

This repository holds **only SHA-256 fingerprints**. The research project itself is kept private.

## What this proves

I test whether a bank gains by adding a sleeve of niche funds (low demand one by one, significant together) to a core exposed to AI, with shared liquidity logistics: the *Amazon vs Walmart* idea applied to finance, here on real private-credit funds (2023-2026) and on listed US equity ETFs (H19-H22).

Before each launch since 16 October 2026, I wrote down the rules, froze the data and the code, and recorded their fingerprints here. Step 16 (launched 10 October) was fingerprinted in the private journal before launch and published here on 16 October. A fingerprint changes completely if a single character of the file changes. Anyone can later recompute the fingerprint of a file I share and check that it matches the one published here, at the date shown by GitHub.

How to check a file: `shasum -a 256 <file>` (macOS/Linux) or `Get-FileHash <file> -Algorithm SHA256` (Windows).

Private repository snapshot: commit `fa42baa550ee5e69fae624fa2ae14cbdee2051d9` (16 Oct 2026). Fingerprints below are those of each file on the date of its deposit; every earlier fingerprint of the protocol and of the journal matches the exact beginning of the current file.

## Pre-registration texts and audit trail

| File | Content | SHA-256 |
|---|---|---|
| `rapport/preenregistrement_h17_h18.md` | Pre-registration of H17 and H18 (validated 14 Oct 2026) | `5bc5f346f180b2b2383908d0f7cccfe197e4e330add239b5ed065b9f2a34e902` |
| `rapport/specification_h17_h18.md` | Code specification | `31111aac34236cf95ac752313e8c6ada3ab46cdac8c540a42ff33e75f26341d1` |
| `rapport/protocole_validation.md` | Full protocol, with dated amendments (sections 13-15), as deposited on 16 Oct 2026 before the H17-H18 launch (first 2,946 lines of the current file) | `600dc209b44c4cc1d59deedacf33ba5c1f56fbbe4aa10f28f5f2c74b2e8e5ec1` |
| `rapport/journal_des_essais.csv` | Trial journal (every decision and run, dated), as deposited on 16 Oct 2026 before the H17-H18 launch (first 104 lines of the current file) | `fd714a4577e9f3697dfc62f085d729448f5d81ff2108f83e920854c2bab2d039` |

## Frozen data (public SEC EDGAR filings, frozen 14 Oct 2026 unless stated)

| File | Content | SHA-256 |
|---|---|---|
| `data/credit_prive_panel_h17_h18.csv` | Panel: 65 private-credit funds, 2021Q4-2026Q3 | `4654eb01ef543ba661512ac74991970c6e7df21bb50d0ecf75a1680acf5a3cde` |
| `data/credit_prive_panel.csv` | Earlier frozen panel (step 16, frozen 9 Oct 2026) | `460098493740acb1891de5b4b58c2f17565600d3e9274dc60ea7e534bc7277f9` |
| `data/credit_prive_fonds.csv` | Frozen fund list (step 16, frozen 9 Oct 2026) | `0138b53008988513466b081a6b1b654b14739f62ff4c2990319ec8b96918ca99` |
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

## Dated forecasts (fingerprint pushed on the launch day, except H17/H18: pushed on 17 October, one day after the launch, as recorded in the trial journal; no Q4 2026 data existed yet)

- H17/H18: share of fresh money going to niche funds in Q4 2026 (`resultats/h1718_prediction_4T2026.csv`), computed by the single launch of 16 October 2026.  
  SHA-256: `55f5049d925e3a049f7b9145f238c7b2ba1e1d1e017d9408bd752eb413986c69`
- H21-2026: flows into the niche ETFs of cohort E2 (3 niche ETFs; the cohort and its event date are set by the Fidelity list fingerprinted below), against 231 control niches (`resultats/h1921_h21_2026_prediction.csv`), frozen by the single launch of 18 October 2026 before any month of its window was read. Expected power is 0.016 (far below 0.80), so it is published as a reading, not a counted test.  
  SHA-256: `3a46a8d54eb71b78a289d6d345c5511dbd7a69f9c7bfe69d4b0c692bd96ae03f`
- Step 16: Q4 2026 redemption requests of 7 funds (`resultats/etape16_previsions_4T2026.csv`), not yet computed. The file will be frozen, and its fingerprint pushed here the same day, by 15 November 2026 at the latest and, for each fund, before that fund files the final amendment (SC TO-I/A) or 8-K letter of its Q4 2026 tender, whichever comes first.
- The forecasts are scored in 2027, once the Q4 2026 filings are public; the files are published with the score.

## H19-H21 (long tail of US ETFs, pre-registered 16 October 2026)

| File | Content | SHA-256 |
|---|---|---|
| `rapport/preenregistrement_h19_h21.md` | Pre-registration of H19, H20, H20-BlackRock, H21, H21-2026 | `014f816836bdd593860b29ee28dff570979899c389ba2ba9a82e34e8afadb6f6` |
| `data/etape19_21_releves/GEL_manifeste.csv` | Freeze manifest of all collected SEC data and scripts (1,544 files), 17 October 2026 | `98ccceb7670cebdab3e8cb69ec2858130075318a4a96802e6c4c70adc6bef14c` |
| `data/etape19_21_releves/fidelity_service_fee_list_20260914.txt` | Fidelity list (not shared): dates the event of the H21-2026 forecast and forms its groups; its dates also set the H21 placebo years | `95628acef50d98d8516571f7e6de3bcbc6ea6ebdcdf61ff799d099ebddc480b5` |

### H19-H21 code and structures (deposited after the dry run, before the single launch)

| File | Content | SHA-256 |
|---|---|---|
| `data/etape19_21_releves/GEL_manifeste.csv` | Freeze manifest (1,544 files) | `98ccceb7670cebdab3e8cb69ec2858130075318a4a96802e6c4c70adc6bef14c` |
| `rapport/preenregistrement_h19_h21.md` | Pre-registration text | `014f816836bdd593860b29ee28dff570979899c389ba2ba9a82e34e8afadb6f6` |
| `rapport/protocole_validation.md` | Full protocol, with H19-H21 inscribed on 16 Oct 2026 (first 3,823 lines of the current file) | `50f4a5ec7af9f1926555047fde59268d213a82dd896943791fc8632793512f93` |
| `resultats/h1921_structures.csv` | Which funds enter each test (counts only, no values) | `25ffb9b11aa259914c317f7685307f90bb80729b15a7b329c9c9f8925e49f75e` |
| `R/longue_traine_h1921.R` | H19-H21 tests | `d29a3dffd5d673c48fab05c973fd65db2bc7a256e90c61b2e7df07aabda1be2f` |
| `scripts/19_21_blackrock_main.R` | H20-BlackRock hand reading (only if the script cannot read the table) | `0876379807d85032b272d2c6df9e13ca374d1f58145b5aa26d922fc491b14bb1` |
| `scripts/19_21_blanc.R` | Dry run on a fictitious panel | `c59cf33e1e804b865a76402f4f6259cd068043619cc1f79cb2949159dd357b59` |
| `scripts/19_21_lancement.R` | Single launch | `cd9274c1ee807e355a2dd39ce99cffb60601ae089ac5ab72c9b6edb20fd8fd79` |
| `scripts/19_21_preparation.R` | Structures | `532071acbf934fbebaa23286be8ed8ff3eced70137f0620456c1bf4b0a547748` |
| `R/credit_prive.R` | Step 16 code | `7ebf03944c6d667226470df73968d1848ac6ad3682b8c3de159ce75721239ed8` |
| `R/logistique.R` | Step 16 code | `6c2b3dcbacca9b1fb63828b788f02df0c0109258272685e98ccbd5fa8b9525fe` |
| `R/validation.R` | Step 16 code | `f0fc435a1f0ebd2ffbcd664c7bfa754f3e3a136bba3860042be8ba37be5c7dfd` |
| `scripts/16_entrepot_credit_prive.R` | Step 16 launch | `44ff004a5615bbce5620a15ff6332f8b539b8f1f6a9df6ccc75e1262caa8cea4` |
| `scripts/16b_previsions_4T2026.R` | Step 16 dated forecasts | `c3e3a038566ac4f7e28d50c29ecb67e3da6b607eb0dfd60d2e6b443c95ff5b46` |
| `tests/test_h1921.R` | Unit tests (143 blocks) | `c93ea71259a8b2591e090511d6b4593f4dc393a3c8088480be8c37b7b9b59df1` |
| `rapport/specification_h19_h21.md` | Code specification, with the dated decisions of 17 October 2026 (sections 11.7-11.8) | `686282aa248d6e27e8962548f6b5f9037eccf6689f48254a4ba44ab96fc3e167` |
| `resultats/h1921_empreintes_4bis.csv` | List of the fingerprints above | `8cbe8e7a61ce7bfdb44e5411e1940cbc77e16be21ac78ae28e45e85b320befca` |

Two rules were changed on 17 October 2026, before the launch and without seeing any value: the threshold of H20 version (a) was lowered from 100 to 40 niche series after the structures counted 48 (in favour of the thesis; written on every H20 verdict), and a single hand reading of the BlackRock table is allowed if the script cannot read it. Both are recorded in the trial journal.

## H22 (long tail on an easy-access app, pre-registered 20 October 2026)

Question: on Robinhood in summer 2019, does a niche ETF have at least twice the clients of an ETF of the same size from the same issuer? The data, rules and code are fixed before any client count is read; the frozen data and the code are fingerprinted below, before the single launch.

| File | Content | SHA-256 |
|---|---|---|
| `rapport/preenregistrement_h22.md` | Pre-registration of H22 (validated 20 Oct 2026) | `c053ec259d88bda6e404eb7cdbc0a248eef951c85ce347d6a05a8ec79d273873` |
| `data/etape22_releves/ligne0/decisions_utilisateur.md` | Owner's dated answers to the pre-registration questions | `bce1656cc26af978eaee9cbf5479bda751f693180838afd90ee733463c53f3f1` |
| `rapport/protocole_validation.md` | Full protocol, with H22 inscribed on 20 Oct 2026 (first 4,796 lines of the current file) | `a7fe81a7a9060f72ad59a850eeedcb730b26d623144620711191fdef1d6cd590` |
| `data/h22_dates.csv` | Event dates checked on primary sources | `3b88e53b8f69f867f3137a3dde6d5c351442bbbe7bfce1bd573bdf03b2a2bd8b` |
| `data/brut/h22/MANIFESTE_robintrack.csv` | Fingerprints of the 2,216 Robintrack ETF files used (public archive) | `7b129c433ebadae9fb93571dc248dcdeb340d19cf7733ed9631f8ddacef188e2` |
| `robintrack-popularity-history.tar.gz` | The public Robintrack archive as downloaded on 18 Oct 2026 (528,844,491 bytes) | `be9ba55ed99a11feb6dbb759ca51d97ad56e9bb0d637ca260c6c75d61c8afac6` |

### H22 freeze (23 October 2026, before any client count is read)

| File | Content | SHA-256 |
|---|---|---|
| `data/h22_gel_manifeste.csv` | Freeze manifest of the H22 data (81 files: sample, cohort, surveys, Bloomberg export workbooks, copies of primary sources) | `0fda9074783a1298fa9a3437fe7c2afdd7df42ee5789e9697585ee92ad8d7939` |
| `resultats/h22_empreintes_gel.csv` | Fingerprint of each frozen file (no values) | `2d4f3f3f65e95b8e2d96b2bf3debcb5aab46d1c8c609bb8835a5c521de4830c5` |
| `data/brut/h22/MANIFESTE_robintrack.csv` | Robintrack files, each checked against this manifest at the freeze (2,216 files) | `7b129c433ebadae9fb93571dc248dcdeb340d19cf7733ed9631f8ddacef188e2` |

### H22 code and structures (deposited after the dry run, before the single launch)

| File | Content | SHA-256 |
|---|---|---|
| `resultats/h22_structures.csv` | Which ETFs enter the test (counts only, no values) | `7fd082dd2bae680b69512da8401458a6c346c215aa1520b1cd11e7e7362442d5` |
| `R/longue_traine_h22.R` | H22 test | `05c522ec182764774b5358320350df561e1b9c777a3a32d5ca50c422cd789f83` |
| `scripts/22_preparation.R` | Surveys, freeze, structures | `7dccac657973f9ebc0624a06ae5747043820854c15647e49eebc7351bd1d25c0` |
| `scripts/22_blanc.R` | Dry run on fictitious panels | `aaf7df5ed62acaea42ae5b2b4c7f5cdb0aa97c27b2aba88e27132080eff62615` |
| `scripts/22_lancement.R` | Single launch | `536ad6b22a36b1f5947480a914a136ed8ed2a9ebf3f17ce05db80ba73037eb84` |
| `tests/test_h22.R` | Unit tests (44 blocks) | `939c9633f63c55465c465a85a4c4d33c89f1e0ca577ebd6975ebb84ced2e3a25` |
| `rapport/specification_h22.md` | Code specification (version 1.2) | `c6cd660605edb2e5fa067c5ca5e1fb05f6e7a66fab9c9ddb1034a9737e881383` |
| `resultats/h22_empreintes_4bis.csv` | List of the code fingerprints, including the shared code (unchanged, same fingerprints as in the H19-H21 table above) | `2f8e07e54f1e7433bda709a11026fd4c5f8eb79c08399cad7344eb57b4f39ed6` |

Decided between 21 and 23 October 2026, before the launch and without reading any client count, all recorded in the trial journal:
- ETFs renamed since 2020 are matched to the Bloomberg export by their 2020 symbol, else by their 2026 ticker, always checked by CUSIP (a departure from the letter of the text, written on every result that uses it).
- The dry run on fictitious panels finds 77 false alarms out of 1,000 in the least favourable null family, above the 75 allowed. Under the pre-registered rule, the official verdict of H22 will therefore be "inconclusive" (1 trial).
- A retained verdict, fixed before the launch, judges the false alarms at the Monte-Carlo margin of error (exact 90% interval [6.36%; 9.23%], which contains the 7.5% cap) and applies every other rule unchanged. The text forbids using a margin in favour of the thesis, so the retained verdict is published beside the official one and never replaces it.
- Power of the two-p rule if niches truly have twice the clients: 0.846. Chance of a full "passes" in that case (all versions held): 0 under the official rule, 0.346 under the retained rule; with no effect: 0 out of 1,000 under both.

### H22 conditional reading (declared 23 October 2026, before the launch)

A separate reading, computed by its own script after the H22 result line, without changing the official or retained verdicts of H22 and without counting as a trial. Judged condition: niches whose price per share in Q3 2019 is in the two cheapest fifths of the other ETFs (45 niches on 20 themes); it is supported if those niches have at least 3 times the clients of ETFs of the same size, price and issuer, with both p-values below 0.05. Two descriptions without verdict: specialist issuers and recent ETFs.

| File | Content | SHA-256 |
|---|---|---|
| `R/longue_traine_h22c.R` | Conditional reading | `3b2617ebd09ea27f3bad06b04afe6784a9c687325cfa74a2ef502be508fd064f` |
| `scripts/22c_conditions.R` | Its dry run and reading | `165a13adcf1ff446ae4ef76afc2fb77ba3194e8e3887376d4d7c43f8b42c8265` |
| `tests/test_h22c.R` | Unit tests (21 blocks) | `5f6abb9a76c53bd93db9d2a20c73b2ef3e0acc06261ee4fd3719209cdb860111` |
| `rapport/specification_h22c.md` | Specification | `9bb29d1c7264ba1e87b3184043174293b792a4efb9925956c32805fa152cd0e7` |
| `resultats/h22_conditions_repetition.csv` | Its dry run on fictitious panels | `89ed64da1a86e7deca73cf186915d8464aaf8398e5effd41e0e9430e917c8922` |

- Dry run: power of the two-p rule 0.91 (455 of 500) at three times the clients; false alarms at most 4.4% in the three null families; testable.
- The threshold of three was chosen by the owner on 23 October 2026, knowing the power (0.616 at twice, 0.91 at three times), after the blindness incident below; the reading carries this mention.
- Blindness incident, 23 October 2026, after the freeze and the dry run: a web-research agent displayed the Q3 2019 Robinhood holder counts of 13 ETFs, 9 of them in the H22 sample (5 niches). All H22 rules, code and data were already frozen; no value was used in any computation. The trial journal records it; the H22 result will carry it.

## Official results (as of 23 October 2026)

Each official verdict is the one written in the trial journal by the single launch. Verdicts retained after a launch are shown apart, with their date; they never replace the official verdict.

| Test | Single launch | Official verdict | Retained after the launch (18 Oct 2026) |
|---|---|---|---|
| H16 | 10 Oct 2026 | Not testable | - |
| H16b | 10 Oct 2026 | Does not pass | - |
| H17a, H17b-families, H17b-catalogue | 16 Oct 2026 | Do not pass (H17b-catalogue: inconclusive) | - |
| H18 (i), (ii), (iii) | 16 Oct 2026 | Do not pass (H18 (ii): inconclusive) | - |
| H19 | 18 Oct 2026 | Does not pass | Partly passes |
| H20 | 18 Oct 2026 | Partly passes | Passes |
| H21 | 18 Oct 2026 | Not testable (power) | - |
| H20-BlackRock | 18 Oct 2026 | Not testable | - |
| H22 | Not yet launched (official dry run: inconclusive in advance; retained rule: testable) | - | - |

Retained after the launch: for H19, the 5% threshold is judged reached within the margin of error (except version (c)); for H20, version (d) is judged on the measure without mixed series in both periods. Both decisions are dated in the trial journal.

Whole project (28 pre-registered tests, September-October 2026): 3 supported, 1 partly supported, 3 not testable, 21 not supported or inconclusive. With the verdicts retained on 18 October 2026: 4 supported, 1 partly supported. H12 (bank profitability, simulation): not supported in general (55% of simulated worlds, 75% required); supported under the conditions measured for Morgan Stanley (98%) and J.P. Morgan (81%), a model update rather than a new test. Tests launched before 16 October 2026 (up to H16b) have no fingerprint published here before their launch; their rules are in the protocol fingerprinted above.

Independent research: not investment advice, and no affiliation with any firm named here.
