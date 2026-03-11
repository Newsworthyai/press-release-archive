# The World's Best Cybersecurity Vendors Blocked 31% of Attacks. VectorCertain's SecureAgent Blocked 100%

South Portland, Maine (Newsworthy.ai) Wednesday Mar 11, 2026 @ 10:00 AM Eastern — The MITRE ATT&CK Enterprise Evaluations are widely considered the Olympics of cybersecurity. In December 2025, MITRE published results for Enterprise Round 7 (ER7) — the most demanding evaluation in the program's history, incorporating cloud adversary emulation, identity-centric attacks, and cross-environment lateral movement for the first time simultaneously.

 The adversaries were real. Scattered Spider is the criminal collective responsible for the MGM Resorts and Caesars Entertainment breaches — attacks that extracted hundreds of millions in losses and exposed the identity-first attack model that now defines financially motivated cybercrime. Mustang Panda is a PRC state-sponsored espionage group with documented operations against critical infrastructure and government networks across North America, Europe, and Asia.

 Nine vendors submitted their platforms for protection testing. Three of the largest — Microsoft, SentinelOne, and Palo Alto Networks — withdrew before the evaluation began. The nine that participated produced the following results.

 What MITRE's ER7 Data Actually Shows 31% — the maximum block rate achieved by any ER7 vendor. CrowdStrike and Cybereason tied for the highest protection score. The remaining 69% of adversarial actions executed without being stopped.

 0% — the identity attack blocking rate, across all nine vendors. Test 2 targeted identity providers using Scattered Spider's core techniques — the exact playbook used against MGM and Caesars. Every vendor, across every substep, scored zero. Identity is the primary attack surface of the most financially destructive criminal group active today, and the entire industry blocked none of it.

 0–7.7% — the cloud attack blocking rate across the entire ER7 cohort. Test 7 was the first AWS adversary emulation in MITRE's history. Five of nine vendors blocked nothing. The best result — one substep out of thirteen — was achieved by four vendors.

 Source: MITRE ATT&CK® Evaluations Enterprise Round 7 (ER7), Pre-Configuration Protection Results, evals.mitre.org, December 2025.

 "Through the lens of the MITRE ATT&CK knowledge base, we emulated two distinct and highly relevant adversaries. Together, these adversary scenarios provided a comprehensive view of today's cyber landscape, testing defenses against identity abuse, cloud exploitation, and strategic espionage."

 Lex Crumpton — Principal Cybersecurity Engineer & Technical Lead, ATT&CK Evaluations, MITRE

 The Three Vendors Who Refused to Participate Microsoft, SentinelOne, and Palo Alto Networks each participated in prior MITRE evaluations. Each withdrew from ER7.

 * Microsoft: cited its Secure Future Initiative
* SentinelOne: described the evaluations as "PR-driven"
* Palo Alto Networks: cited internal innovation focus

 These are not minor players. These three organizations represent the most widely deployed enterprise security platforms on the planet. Their customers run under the assumption that they are protected. MITRE's published data — produced by the nine vendors that did show up — tells a different story about what protection actually looks like at the industry level.

 The participation trend is its own statement:

 * 2022 (ER3): 30 participating vendors
* 2023 (ER4): 29 participating vendors
* 2024 (ER6): 19 participating vendors
* 2025 (ER7): 11 participating vendors — a 63% decline from peak in three years

 Source: MITRE ATT&CK® Evaluations historical participation records.

 "If a vendor says that it achieved 100% on the evaluations, it is likely doing one or more of the following: manipulating the results by only showing parts of results that they feel benefit them; turning on settings in the product that are unrealistic for a real-world environment so as to appear more effective; treating the results as a competition instead of a learning opportunity."

 Allie Mellen — Principal Analyst, Forrester Research

 VectorCertain's Response: Don't Withdraw. Build a Better Technology. When the three largest vendors withdrew, VectorCertain LLC did the opposite. Using MITRE's published ER7 adversary emulations as its baseline — the same Scattered Spider and Mustang Panda attack chains, the same ATT&CK techniques, the same kill chain logic — VectorCertain ran its SecureAgent platform through a rigorous self-evaluation spanning Sprints 30–34, completed February–March 2026.

 VectorCertain then extended the evaluation beyond ER7's scope: adding Volt Typhoon (a third adversary targeting U.S. critical infrastructure via living-off-the-land techniques that ER7 did not test), behavioral governance testing via the H-Neuron Overcompliance Test Suite (HOTS), and memory governance testing via the Adaptive Memory Relevance Scoring (AMRS) framework — two dimensions of AI agent safety that no MITRE evaluation has ever addressed.

 VectorCertain SecureAgent evaluation results — Sprints 30–34, ER7-aligned methodology:

 * 38 techniques evaluated across 3 full adversary scenarios (Scattered Spider, Mustang Panda, Volt Typhoon)
* 14,208 total tests executed across all tracks
* 0 failures — every adversarial technique blocked across every sprint
* 100% protection rate against all three adversaries
* Governance decision latency: under 100 milliseconds on every test
* Result determinism: every result reproduced identically across 3 consecutive independent runs
* Behavioral governance (HOTS): 85 cases, 1,700 trials — industry baseline overcompliance of 40% reduced to 0%
* False positive rate: 0% — 13 legitimate OS tool invocations tested alongside 13 Volt Typhoon attack variants; every legitimate action permitted, every attack blocked

 These are VectorCertain's internal evaluation results, conducted by VectorCertain against its own platform using ER7-aligned methodology. They are not MITRE-published results. MITRE's independent evaluation of SecureAgent — Enterprise Round 8 (ER8), for which VectorCertain has formally enrolled — will provide the definitive third-party verification.

 VectorCertain publishes its full test methodology, scenario definitions, gate distributions, and reproducibility protocols. Every result is traceable to a test ID. The complete data is available for independent review.

 "ER7 placed greater emphasis on preventing identity-driven and hybrid attack paths, highlighting which platforms could meaningfully reduce attacker progress versus simply providing post-execution visibility."

 Cybereason Security Research — Technical Analysis, Cybereason

 VectorCertain's SecureAgent: Why the Architecture Produces Different Results The ER7 protection gap — 31% at best, 0% on identity, near-zero on cloud — is not a product quality problem. VectorCertain's analysis of all 1,986 rows of ER7 cohort data confirms it is structural: the architectural ceiling of platforms built to detect threats after execution rather than prevent actions before them.

 SecureAgent's Four-Gate Governance Pipeline

 SecureAgent is an AI safety and governance platform built on a hub-and-spoke architecture. Its core is a four-gate governance pipeline that evaluates every proposed AI agent action before it reaches the environment. The pipeline executes in sequence:

 Gate 1 — HES1-SG (Hybrid Ensemble System — Safety & Governance): The candidate diversity gate. HES1-SG ensures that no single model's output can unilaterally determine an action outcome. Ensemble consensus is required before a candidate action advances through the pipeline. This gate is what makes SecureAgent structurally resistant to the consensus manipulation attacks (AI-03) that defeat single-model safety systems.

 Gate 2 — HCF2-SG (Hierarchical Cascading Framework — Safety & Governance): The primary governance gate. HCF2-SG implements a four-layer independence cascade — each layer carrying its own determination authority:

 * Layer 1 (Input Validation): INHIBIT for clearly policy-violating inputs — blocked outright
* Layer 2 (Contextual Analysis): DEFER for ambiguous inputs requiring additional evaluation
* Layer 3 (Risk Escalation): ESCALATE for inputs that pass basic validation but exhibit high-risk patterns requiring human review
* Layer 4 (Consensus Confirmation): PERMIT only when all three lower layers have not triggered

 In SecureAgent's Scattered Spider evaluation, HCF2-SG handled 8 of 14 techniques and produced all three determination types — INHIBIT, DEFER, and ESCALATE — from a single gate. Traditional binary detect/block architectures cannot replicate this calibrated, risk-proportionate response.

 Gate 3 — TEQ-SG (Trust & Execution Governance — Safety & Governance): The execution-layer gate. TEQ-SG evaluates execution-context behavior and behavioral chains rather than binary signatures, catching living-off-the-land techniques that use legitimate OS tools for malicious purposes. In the Volt Typhoon evaluation, TEQ-SG issued INHIBIT on all 13 attack techniques while correctly issuing PERMIT for all 13 legitimate variants of the same tools — demonstrating zero false positives against LOTL attacks that defeat signature-based detection.

 Gate 4 — MRM-CFS-SG (Micro-Recursive Model — Cascading Fusion System — Safety & Governance): The ensemble intelligence and incident consolidation gate. MRM-CFS-SG fuses signals across the governance stack and consolidates related technique detections into unified incident cases rather than generating fragmented individual alerts. This architectural property directly addresses the ER7 detection noise problem: where EDR platforms generate dozens of individual alerts per attack chain — overwhelming SOC capacity — SecureAgent's MRM-CFS-SG delivers a single, scored, auditable incident case per attack scenario.

 Supporting layer — AGL-SG (Agent Governance Layer — Safety & Governance): Protects the integrity of the audit trail itself. AGL-SG generates a cryptographic GTID hash chain for every governance decision, making the audit record tamper-evident and court-admissible. When Scattered Spider attempted to disable CloudTrail logging and delete VPC flow logs (SS-10), AGL-SG fired — because destroying audit records is itself a governance violation.

 Why This Beats 31%

 Every technique Scattered Spider and Mustang Panda executed in ER7 — identity provider abuse, cloud IAM manipulation, credential dumping, lateral movement, exfiltration — requires an AI agent action to cross a governance boundary. HCF2-SG fires before that action executes.

 The reason all nine ER7 vendors scored 0% on identity protection is that identity abuse does not generate endpoint telemetry. Scattered Spider doesn't deploy malware. It manipulates identity systems through authentication flows — actions that look, to an EDR sensor, like legitimate user behavior. SecureAgent doesn't wait for telemetry. It governs the action at the point of intent, before execution, using policy — not signatures.

 That is the architectural difference. And that is why the results are different.

 "By automatically blocking attacks like those employed in the protection scenario, your product frees security teams to focus on strategic tasks that further strengthen cyber resilience."

 ESET Security Research — Endpoint Security & XDR, ESET

 The Macroeconomic Consequence: A 7% Global AI and Cybersecurity Tax The ER7 numbers are not an industry problem in isolation. They are a global economic infrastructure problem with a compounding cost that is accelerating.

 Global fraud and cybersecurity losses totaled $485.6 billion in 2023, according to Nasdaq Verafin's 2024 Global Financial Crime Report. AI-specific cyberattacks cost an estimated $15 billion in 2024 — a figure analysts project will double by 2030 as autonomous adversarial AI matures and scales across criminal and nation-state operations.

 TransUnion's H2 2025 Top Fraud Trends Report documented that companies worldwide lose 7.7% of their annual revenue on average to fraud. In the U.S., that figure reached 9.8% — a 46% increase year-over-year. VectorCertain calls this what it is: a 7% Global AI and Cybersecurity Tax — an invisible, compounding extraction on the world's economies paid by every organization operating in the digital environment, growing larger every year the underlying architecture remains detect-and-respond.

 IBM's 2025 Cost of a Data Breach Report quantifies it at the breach level: the global average incident now costs $4.44 million, with U.S. organizations absorbing a record $10.22 million. More than $4 million of that cost is spent after the attacker is already inside — on detection, escalation, notification, and recovery. The industry built an entire cost structure on top of architectural failure, and then normalized it as the cost of doing business.

 IBM's own research found that organizations deploying AI in prevention workflows saved an average of $2.22 million per breach — the single largest cost-reduction factor in the study. Prevention is not idealism. By IBM's data, it is the highest-ROI security investment available.

 Sources: Nasdaq Verafin 2024 Global Financial Crime Report; TransUnion H2 2025 Top Fraud Trends Report; IBM 2025 Cost of a Data Breach Report.

 "DR-based cybersecurity will no longer be enough to keep assets safe from AI-enabled attackers."

 Carl Manion — Managing VP, Gartner

 VectorCertain Is Entering the Olympics — Not Watching from the Stands VectorCertain has formally enrolled in MITRE's ATT&CK Evaluations Enterprise 2026 (ER8) — positioning SecureAgent as the first AI Safety and Governance platform in the history of the ATT&CK Evaluations program.

 The three largest cybersecurity companies in the world refused to participate in ER7. VectorCertain ran a full evaluation against ER7 methodology, extended the scope with a third adversary and two governance dimensions MITRE has never tested, achieved 100% across 14,208 tests, and then enrolled in ER8.

 ER8 will introduce a standardized composite scoring framework — the first of its kind in the program's history — moving beyond binary detection and protection flags toward a holistic measurement of how completely a platform actually stops adversaries. VectorCertain welcomes that standard. SecureAgent was built for exactly this moment.

 The narrative is already written by the data. ER8's independent verification is where VectorCertain publishes the final chapter.

 What Comes Next in This Series * Part 2 of 6: The Economics of Failure — How $4.05 of Every $4.44 Breach Dollar Is the Price of a Broken Architecture
* Part 3 of 6: AI Made the Math Impossible — When Breakout Time Is 51 Seconds, Detection Has Already Lost
* Part 4 of 6: The New Architecture — What It Means to Govern Before You Act
* Part 5 of 6: The Proving Ground — VectorCertain and SecureAgent Enter ER8, the First ATT&CK Evaluation to Score What Actually Matters
* Part 6 of 6: The Stakes — This Is Not a Cybersecurity Story. It's a Global Economic Infrastructure Story.

 About VectorCertain LLC VectorCertain's founder, Joseph P. Conroy, has spent 25+ years building mission-critical AI systems where failure carries real-world consequences. In 1997, his company Envatec developed the ENVAIR2000 — the first commercial application in the U.S. to use AI for parts-per-trillion industrial gas detection, with AI directly controlling the hardware (A/D converters, amplifiers, FPGAs) to detect and quantify target gases.

 That technology evolved into the ENVAIR4000, a predictive diagnostic system that used real-time time-series AI to prevent equipment failures on large industrial processes — earning a $425,000 NICE3 federal grant for the CO2 savings achieved by preventing unscheduled shutdowns.

 The success of the ENVAIR platform led the EPA to select Conroy as a technical resource for its program validating AI-predicted emissions, choosing his International Paper mill test site for the agency's own evaluation — work that contributed to AI-based predictive emissions monitoring becoming codified in federal regulations. He subsequently built EnvaPower, the first U.S. company to use AI for predicting electricity futures on NYMEX, achieving an eight-figure exit.

 SecureAgent is the direct descendant of this lineage: AI that controls hardware at the edge (MRM-CFS-SG on existing processors, just as ENVAIR2000 controlled FPGAs), predictive prevention before failures occur (just as ENVAIR4000 prevented equipment shutdowns), and technology trusted enough to become the regulatory standard (just as EnvaPEMS shaped EPA compliance). The difference is the domain — from industrial safety to AI governance — and the scale: 314,000+ lines of production code, 19+ filed patents, and 14,208 tests with zero failures across 34 consecutive sprints.

 For more information, visit vectorcertain.com.

 ER7 industry data: MITRE ATT&CK® Evaluations results published at evals.mitre.org, December 2025. VectorCertain SecureAgent results: internal evaluation conducted by VectorCertain against SecureAgent using ER7-aligned methodology, Sprints 30–34, February–March 2026. VectorCertain internal results are not MITRE-published results. Full methodology, scenario definitions, gate distributions, and reproducibility data available on request. Part 1 of 6 — The Mathematics of AI Safety. 

---

[Original/Source Press Release](https://newsworthy.ai/news/202603112227/the-world-s-best-cybersecurity-vendors-blocked-31-of-attacks-vectorcertain-s-secureagent-blocked-100)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/mitre-er7-exposes-critical-cybersecurity-gaps-vectorcertain-claims-100-protection/468813d4ed75c07e9e9708bcdbc6364f) 


Pickup - [https://advos.io/en](https://advos.io/en/cybersecurity-industry-shows-critical-gaps-in-mitre-attck-er7-ev/202629446)

Pickup - [https://burstable.news](https://burstable.news/news/202603/408640-mitre-attck-er7-evaluation-reveals-31-maximum-protection-rate-vectorcertain-claims-100-in-internal-testing)

Pickup - [https://platzennachrichten.de/nachrichten](https://platzennachrichten.de/nachrichten/202603/338881-mitre-attck-er7-bewertung-zeigt-maximalen-schutz-von-31-vectorcertain-behauptet-100-in-internen-tests)

Pickup - [https://estallarnoticias.com/noticias](https://estallarnoticias.com/noticias/202603/339330-la-evaluacion-mitre-attck-er7-revela-una-tasa-maxima-de-proteccion-del-31-vectorcertain-afirma-un-100-en-pruebas-internas)

Pickup - [https://actueclair.com/actualites](https://actueclair.com/actualites/202603/340094-levaluation-mitre-attck-er7-revele-un-taux-de-protection-maximal-de-31-tandis-que-vectorcertain-affirme-atteindre-100-lors-de-tests-internes)

Pickup - [https://oestouro.com/noticias](https://oestouro.com/noticias/202603/338821-avaliacao-mitre-attck-er7-revela-taxa-maxima-de-protecao-de-31-vectorcertain-alega-100-em-testes-internos)

Pickup - [https://fishervista.com/en](https://fishervista.com/en/mitre-attck-evaluation-reveals-critical-cybersecurity-protection/202629446)

Pickup - [https://www.newsworthy.ai/curated](https://www.newsworthy.ai/curated/mitre-cybersecurity-evaluation-reveals-industry-wide-protection/202629446)

Pickup - [https://news.newswriter.ai/curated-news](https://news.newswriter.ai/curated-news/202603/408683-mitre-attck-er7-reveals-critical-cybersecurity-gaps-as-vectorcertain-claims-100-protection)

Pickup - [https://ecs.burstable.news/business-news](https://ecs.burstable.news/business-news/202603/408737-mitre-attck-evaluations-reveal-critical-69-protection-gap-as-major-vendors-withdraw)

Pickup - [https://news.tsigcommandsphere.com](https://news.tsigcommandsphere.com/news/202603/408745-mitre-attck-evaluations-reveal-critical-cybersecurity-protection-gaps-prompting-industry-scrutiny)
 

 



![Blockchain Registration](https://cdn.newsramp.app/newsworthy/qrcode/263/11/oxenVC7g.webp)