# BittBridge (Subnet 183) — deAI Video Transcripts

Transcripts for the **UConn BittBridge / decentralized-AI (deAI)** bonus videos — the OPIM 5509 final-project materials (S26 BittBridge), recorded by **Dmitrii Tuzov** and the BittBridge team (Dmitrii, Niharika, Faeze, Ben, Matt). Bittensor **Subnet 183**.

- `transcripts/` — raw caption files (`.srt`)
- `_clean/` — timestamp-stripped plain text
- `scripts/` — AI-polished narrative transcripts

## Companion guide
These transcripts pair with the official **BittBridge guide on GitHub**: **https://github.com/bittbridge/bittbridge** — the subnet codebase + docs (miner/validator setup, model deploy, leaderboard). Watch/read the videos alongside that repo.

## Status
✅ **Transcribed (June 2026).** All 18 videos were shared to Dave as Co-Editor on UConn Kaltura. They had **no captions**, so transcripts were generated locally with **faster-whisper** (`small.en`) from the source audio, then cleaned and polished. Machine captions were **also ordered via Kaltura REACH** on all 18 so the videos carry closed captions for students.

- `transcripts/` — raw Whisper `.srt` (verbatim, with ASR quirks on jargon like "Bittensor")
- `_clean/` — timestamps stripped, reflowed into paragraphs
- `scripts/` — AI-polished narrative (jargon/grammar/capitalization corrected, readable prose)

## Video index (18) — entry IDs

**What is decentralized AI? (4 deAI lectures)**
| Entry ID | Title |
|---|---|
| `1_sm7figw0` | DeAI – lecture #1 |
| `1_w6j2qvml` | DeAI – lecture #2 |
| `1_n9y8vy9a` | DeAI – lecture #3 |
| `1_0f20wgdb` | DeAI – lecture #4 |

**Setting up a wallet & deploying the base miner (7)**
| Entry ID | Title |
|---|---|
| `1_rvkp9ix1` | Bittbridge_miner – 1 Intro |
| `1_hkx86b52` | Bittbridge – 2 Before You Start |
| `1_3ixffibi` | Bittbridge – 3.1 GCP VM Setup |
| `1_3aziuub3` | Bittbridge – 3.2 GCP VM Setup |
| `1_qn3tci3a` | Bittbridge 4.1 Wallets-and-tokens |
| `1_j5kaf79m` | Bittbridge 4.2 Wallets-and-tokens |
| `1_pvm3f7ny` | Bittbridge 5 Miner deployment |

**Deploying basic ML/DL models, leaderboard & custom miners (6)**
| Entry ID | Title |
|---|---|
| `1_djsdjqps` | Bittbridge Linux Basics |
| `1_erp0ki2a` | Bittbridge Codebase Update |
| `1_iib12xl3` | Bittbridge config file changes + linear regression + cart |
| `1_efxpuzat` | Bittbridge How to make changes in models and redeploy |
| `1_nwtohw64` | Bittbridge download actualsvpredicted csv |
| `1_l7i6w9zg` | Bittbridge Leaderboard use |

**Push yourself — train in Colab, deploy on Bittensor (1)**
| Entry ID | Title |
|---|---|
| `1_jg6v904i` | Advanced Models with Colab (Custom_model_feature live demo) |

*Full course context: see `opim5509-transcripts/HuskyCT_course_outline.md` (the Bittensor bonus section).*
