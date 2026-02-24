# 97% Detect-and-Respond. The U.S. Treasury's AI Framework Was Designed for a Threat That Waits to Be Found — Autonomous AI Agents Don't Wait

South Portland, Maine (Newsworthy.ai) Tuesday Feb 24, 2026 @ 1:35 PM Eastern — Yesterday, VectorCertain released the full scope of its AI Executive Order Group (AIEOG) Conformance Suite — the first comprehensive analysis mapping a commercial AI governance platform against the U.S. Treasury Department's Financial Services AI Risk Management Framework (FS AI RMF). Eight documents. 74,000+ words. Every one of the Treasury's 230 AI control objectives analyzed. Every one of the CRI Profile's 278 cybersecurity diagnostic statements mapped. A unified 508-point governance architecture assembled for the first time.

 The headline finding: 97% of the FS AI RMF's 230 AI control objectives operate in detect-and-respond mode, with virtually zero prevention capability.

 Today, we explain what that finding means — in dollars.

 Because the Prevention Gap isn't just a technical limitation. It's an economic one. And the economics are unambiguous: for every dollar spent preventing an AI governance failure, organizations spend ten dollars detecting it and a hundred dollars remediating it. This is the 1:10:100 rule, and it is the central economic argument for what VectorCertain calls the Prevention Paradigm — the principle that AI governance must prevent unauthorized actions before execution, not detect them afterward.

 Every release this week builds on this principle. Today establishes why. Tomorrow reveals where the hardware gap makes prevention urgently necessary. Thursday exposes the autonomous agent threats that make prevention existentially necessary. Friday shows the unified platform that makes prevention actually possible.

 But today is about the math. And the math is devastating.

 The 1:10:100 Rule: Why Prevention Is 10–100x More Economical The economics of cybersecurity have been studied for two decades. IBM's Cost of a Data Breach Report, now in its twentieth edition, provides the most comprehensive dataset. The 2025 report, analyzing 600 breached organizations across 17 industries and 16 countries, reveals a cost structure that makes the case for prevention in terms no CFO can ignore:

 The Cost of Detection

 The average global data breach now costs $4.44 million (IBM 2025). In the United States, that figure rises to $10.22 million — an all-time high, up 9% year-over-year even as the global average declined. For financial services specifically, the average breach costs $5.56–$6.08 million, second only to healthcare's $7.42 million.

 Detection and escalation alone — the cost of simply finding the problem — averages $1.47 million per breach, making it the single largest cost component for the fourth consecutive year. The average time to identify and contain a breach is 241 days. For financial services, detection alone averages 168 days — nearly six months of attackers moving freely through systems before anyone notices.

 The Cost of Remediation

 Beyond detection, organizations face notification costs ($390,000 average), lost business ($1.38 million average), and post-breach response costs ($1.2 million average). For financial services, the costs multiply: regulatory penalties from overlapping frameworks (PCI DSS, SOX, GLBA, state privacy laws), mandatory security improvements, ongoing compliance monitoring, and customer churn — 38% of financial services customers say they would switch institutions after a breach, with stock prices dropping an average of 7.5% post-breach.

 Recovery extends well beyond containment: roughly half of breach costs are incurred after the first year. The total economic impact — direct costs, opportunity costs, regulatory penalties, reputational damage, customer attrition — dwarfs the initial breach figure.

 The Cost of Prevention

 Now compare: organizations using AI-powered security and automation extensively saved $1.9 million per breach compared to those that didn't (IBM 2025). Their breach costs averaged $3.05 million compared to $5.52 million for organizations without these tools — a 45% reduction. Detection time dropped from 321 days to 249 days. Organizations with zero-trust architectures saved $1.76 million per incident.

 But these are still detect-and-respond savings — finding problems faster, not preventing them. The true economic comparison is between organizations that detect a breach in 200+ days versus organizations where the breach never occurs because the unauthorized action was prevented before execution.

 This is the 1:10:100 rule in practice:

 * $1 to prevent: Governance that evaluates and authorizes or inhibits every AI action before execution. Cost: computational overhead measured in fractions of a millisecond and fractions of a cent per transaction.
* $10 to detect: Monitoring systems, SIEM platforms, SOC analysts, alert triage, investigation, escalation. Cost: $1.47 million in detection and escalation alone per breach (IBM 2025).
* $100 to remediate: Notification, legal, regulatory penalties, customer churn, reputational damage, system restoration, ongoing compliance. Cost: the full $4.44–$10.22 million breach lifecycle — plus years of downstream impact.

 When 97% of the Treasury's framework operates in detect-and-respond mode, it locks financial institutions into the $10–$100 end of this curve. The framework provides comprehensive guidance on what to detect and how to respond — and that guidance is valuable. But it provides virtually no technical infrastructure for prevention. And prevention is where the economics are 10–100x more favorable.

 Why 97% Detect-and-Respond? The Architecture of the Gap The Prevention Gap is not a criticism of the FS AI RMF's authors. The framework is comprehensive, well-structured, and represents serious regulatory thinking. The gap exists because the framework was designed during a specific technological window — and that window has closed.

 When the FS AI RMF was developed, the dominant model for AI in financial services was human-supervised AI assistance: models that generate recommendations, analyses, or drafts that humans review before action. In that world, detect-and-respond is a reasonable governance paradigm. The human in the loop is the prevention mechanism. The framework's role is to ensure the detection and response infrastructure works when the human review process fails.

 That model no longer describes reality.

 Autonomous AI agents now outnumber human employees 82:1 in the enterprise (Palo Alto Networks). They execute actions in milliseconds — initiating payments, sending communications, modifying data, executing code — without waiting for human review. The human-in-the-loop prevention mechanism that the framework implicitly relies upon is being removed by the very organizations implementing the framework.

 VectorCertain's conformance analysis classified all 230 AI control objectives across the framework's 23 Governance Action Points (GAPs) according to their governance paradigm:

 Detect-and-Respond Controls (97%): These controls assume that an AI action occurs first and governance responds afterward. They use language like "monitor," "detect," "assess," "evaluate," "report," "review," "audit," "investigate," and "respond." They are essential — but they operate after the fact.

 Prevention Controls (3%): These controls require governance determination before an AI action is permitted to execute. They use language like "prevent," "prohibit," "block," "require authorization before," and "inhibit." They are nearly absent from the framework.

 The practical impact: a financial institution that achieves perfect compliance with every one of the framework's 230 control objectives will have built a comprehensive system for detecting AI governance failures after they occur. It will have built virtually no infrastructure for preventing them.

 In a world of human-supervised AI, this is a limitation. In a world of autonomous agents acting in milliseconds, it is a structural vulnerability.

 The IBM Finding That Validates the Prevention Paradigm IBM's 2025 report contains a finding that deserves special attention in the context of the Prevention Gap:

 97% of organizations that experienced an AI-related security incident lacked proper AI access controls.

 Read that again. Not 97% of organizations. Ninety-seven percent of organizations that were breached. The organizations with proper controls — the prevention infrastructure — overwhelmingly did not appear in the breach dataset.

 The same report found that 63% of organizations lack AI governance policies entirely. Among those that have policies, fewer than half have approval processes for AI deployments. Only 34% perform regular audits for unsanctioned AI. Shadow AI — unauthorized AI tools adopted without IT oversight — was a factor in 20% of breaches, adding $670,000 to the average cost.

 The pattern is consistent: organizations that invest in prevention infrastructure experience dramatically fewer and less costly incidents. Organizations that rely on detection alone pay the full 1:10:100 cost curve.

 This is not a new insight. Engineers have understood this principle for generations. You don't build a bridge that depends on every cable being perfect. You build a bridge that holds when a cable snaps. The discipline of applying this principle to AI governance — designing systems where safety is structural, not dependent on any actor's behavior — is what VectorCertain calls the Prevention Paradigm.

 What the Prevention Paradigm Looks Like in Practice The Prevention Paradigm is not a philosophy. It is an architecture. And it has specific, measurable properties that distinguish it from detect-and-respond:

 Property 1: Governance completes before the action executes.

 In a detect-and-respond system, the AI acts first and governance evaluates afterward. In a prevention system, governance evaluates first and the AI acts only if authorized. This is a temporal distinction with enormous practical consequences: in a prevention system, unauthorized actions never occur. There is nothing to detect, nothing to respond to, nothing to remediate.

 VectorCertain's six-layer prevention architecture completes governance evaluation in 0.27 milliseconds — 185–1,850x faster than the 50–500 milliseconds a typical AI agent takes to execute an action. The governance is faster than the agent.

 Property 2: Safety is structural, not behavioral.

 In a detect-and-respond system, safety depends on the AI behaving as intended — following its instructions, respecting its training, operating within its parameters. When the AI deviates, the detection system must notice.

 In a prevention system, safety does not depend on the AI's behavior. The governance architecture operates independently of the AI's intent. Whether the AI is functioning perfectly or has been compromised, manipulated, or is hallucinating, the governance evaluation occurs before any action is permitted. The No-Blind-Spot Lemma — a mathematical proof embedded in VectorCertain's GD-CSR patent — guarantees that no execution path bypasses governance. Not a policy. A proof.

 Property 3: Prevention costs are per-transaction, not per-incident.

 Detection and remediation costs are incurred per incident — and each incident costs $4.44–$10.22 million. Prevention costs are incurred per transaction — computational overhead measured in fractions of a millisecond and fractions of a cent. The per-transaction cost of governance evaluation is negligible compared to the per-incident cost of breach remediation.

 For a financial services institution processing millions of transactions daily, the total cost of per-transaction prevention governance is a rounding error compared to the cost of a single breach. This is the 1:10:100 rule expressed as infrastructure economics: prevention is not just cheaper — it is cheaper by orders of magnitude.

 Property 4: Prevented actions are recorded with the same fidelity as permitted actions.

 A unique limitation of detect-and-respond systems is that they can only record what happened. Prevention systems record what didn't happen — and why. VectorCertain's architecture records every governance evaluation, whether the action was authorized, inhibited, deferred, or escalated. The company's patent-pending Agent Governance Ledger (AGL-SG) provides the technical implementation: a cryptographically chained Governance Transaction Identifier (GTID) for every agent action attempt, creating an immutable forensic record with cascading containment capabilities when compromised agents are detected. This creates a complete governance record that demonstrates not only that authorized actions were governed, but that unauthorized actions were identified and prevented before execution.

 For regulatory compliance, this distinction is transformative. Instead of demonstrating that the organization can detect failures after they occur, the organization demonstrates that failures are prevented before they occur — and provides a mathematical proof of governance coverage.

 What This Means for the FS AI RMF VectorCertain's analysis is not a call to abandon the FS AI RMF. The framework's 230 control objectives provide comprehensive coverage of the governance domains that matter — from model risk management to data governance to operational resilience. The control objectives are sound. The governance paradigm they are embedded in — detect-and-respond — is the limitation.

 The Prevention Paradigm complements the FS AI RMF by providing the technical infrastructure that makes the framework's control objectives enforceable at agent speed:

 * Where the framework says "monitor," the Prevention Paradigm says "evaluate before execution and monitor continuously."
* Where the framework says "detect," the Prevention Paradigm says "prevent, and record the prevention for audit."
* Where the framework says "respond," the Prevention Paradigm says "the unauthorized action never executed — but here is the complete governance record of why it was prevented."

 This is not a replacement. It is an upgrade — from a framework designed for human-supervised AI to an architecture capable of governing autonomous agents operating at machine speed.

 VectorCertain's AIEOG Conformance Suite demonstrates this mapping in detail across all 230 control objectives and all 278 CRI Profile cybersecurity diagnostic statements. The complete analysis is available in the eight-document suite totaling 74,000+ words.

 The Numbers That Matter For financial services leaders evaluating the Prevention Gap, here are the numbers that frame the decision:

 The Cost of the Status Quo

 * Average financial services breach: $5.56–$6.08 million (IBM 2025)
* Average U.S. breach: $10.22 million — all-time high
* AI-related breach cost premium: $670,000 additional per incident involving shadow AI
* 97% of AI-related breaches in organizations without proper AI access controls
* Average detection time: 241 days globally; 168 days in financial services
* Customer churn post-breach: 38% of financial services customers would switch
* Stock price impact: 7.5% average decline post-breach
* AI-enabled fraud projection: $40 billion by 2027 (Deloitte), $230 billion true economic impact at $5.75 multiplier (LexisNexis)

 The Cost of Prevention

 * VectorCertain governance latency: 0.27 milliseconds per evaluation
* Model footprint: 29–71 bytes — deployable on any processor (details tomorrow)
* Organizations with AI security automation: $1.9 million saved per breach (IBM 2025)
* Organizations with zero-trust architecture: $1.76 million saved per incident
* Prevention-to-detection cost ratio: 1:10 minimum
* Prevention-to-remediation cost ratio: 1:100 minimum
* VectorCertain platform validation: 8,884 tests, zero failures across 293,000+ lines of code with a 1.36:1 test-to-source ratio — 25 consecutive sprints without a single test failure

 "The economics of the Prevention Gap are not subtle," said Joseph P. Conroy, Founder and CEO of VectorCertain. "Every dollar invested in pre-execution governance saves ten to a hundred dollars in detection, response, and remediation. Every breach that is prevented eliminates not just the direct cost, but the regulatory penalties, the customer churn, the stock impact, and the years of downstream recovery. The 97% detect-and-respond finding isn't just a technical gap — it's a $10.22 million-per-incident gap. And the framework that was supposed to close it is, by our analysis, structurally unable to do so. That's why we built VectorCertain."

 Tomorrow: Where the Prevention Gap Meets the Hardware Gap Today we explained the economics of the Prevention Gap — why 97% detect-and-respond is not just a technical limitation but a financial one, and why prevention offers 10–100x cost advantage.

 Tomorrow, we reveal a companion finding that makes the Prevention Gap even more urgent: the Legacy Hardware Crisis. Over 1.2 billion deployed processors in U.S. financial services — ATM controllers, POS terminals, EMV smart cards, core banking mainframes — currently have zero AI governance capability. And we introduce the technology that changes that equation: MRM-CFS, micro-recursive governance models that deploy in 29–71 bytes at 0.27 milliseconds on hardware the industry assumed could never be governed.

 The Prevention Gap tells you why you need pre-execution governance. The Legacy Hardware Crisis tells you where. Thursday's Agent Threat Surface tells you how urgent. And Friday's Unified Platform shows you how.

 The Prevention Paradigm isn't a feature. It's the architecture.

 This Week's Series * Monday: Flagship Announcement — Complete Conformance Suite overview: 97% detect-and-respond finding, six-layer prevention architecture, 508 unified control points, Agent Governance Ledger preview.
* Tuesday: The Prevention Gap (this release) — Why 97% detect-and-respond leaves financial services exposed. The 1:10:100 rule. Why prevention offers 10–100x cost advantage.
* Wednesday: The Legacy Hardware Crisis — 1.2B+ processors with zero AI governance. $40B fraud by 2027. MRM-CFS: 29–71 bytes, 0.27ms, governance without hardware replacement.
* Thursday: The Autonomous Agent Threat Surface — Real-world agent attacks. $25B competitive response. Why detect-and-respond cannot govern agents that act at machine speed.
* Friday: The Unified Platform — 508 points of control. How one platform bridges cybersecurity and AI governance to meet the full scope of the FS AI RMF.

 About VectorCertain LLC VectorCertain LLC is an AI safety and governance technology company headquartered in Casco, Maine. Founded by Joseph P. Conroy, a veteran of mission-critical AI systems with 25+ years of experience building AI for federal agencies including the EPA, DOE, DoD, and NIH, VectorCertain develops the SecureAgent platform — a governance-first AI safety system built on a patented hub-and-spoke architecture with 19+ patent applications providing mathematical certainty guarantees for AI decisions in regulated industries. The company's MRM-CFS technology enables AI governance deployment on existing hardware without replacement, and the Agent Governance Ledger (AGL-SG) provides cryptographically chained accountability for every autonomous agent action. Conroy previously achieved an eight-figure exit with ENVAIR4000, a predictive emissions monitoring system that became EPA standard. He is also the author of The AI Agent Crisis: How To Avoid The Current 70% Failure Rate & Achieve 90% Success (September 2025).

 For more information, visit vectorcertain.com. 

---

[Original/Source Press Release](https://newsworthy.ai/news/202602242174/97-detect-and-respond-the-u-s-treasury-s-ai-framework-was-designed-for-a-threat-that-waits-to-be-found-autonomous-ai-agents-don-t-wait)
                    

[Newsramp.com TLDR](https://newsramp.com/curated-news/ai-safety-report-97-of-treasury-s-ai-rules-can-t-prevent-breaches/7dba62affbf89fec7ea3d89a35cb2922) 


Pickup - [https://advos.io/en](https://advos.io/en/us-treasurys-ai-framework-relies-on-97-detect-and-respond-approa/202628621)

Pickup - [https://burstable.news](https://burstable.news/news/202602/396180-analysis-reveals-97-of-treasurys-ai-framework-relies-on-detect-and-respond-creating-10m-prevention-gap)

Pickup - [https://platzennachrichten.de/nachrichten](https://platzennachrichten.de/nachrichten/202602/337934-analyse-zeigt-97-des-ki-rahmenwerks-des-finanzministeriums-basieren-auf-erkennen-und-reagieren-was-eine-praventionslucke-von-uber-10-millionen-us-dollar-schafft)

Pickup - [https://estallarnoticias.com/noticias](https://estallarnoticias.com/noticias/202602/338308-analisis-revela-que-el-97-del-marco-de-ia-del-tesoro-se-basa-en-detectar-y-responder-creando-una-brecha-de-prevencion-de-mas-de-10-millones)

Pickup - [https://actueclair.com/actualites](https://actueclair.com/actualites/202602/339040-une-analyse-revele-que-97-du-cadre-dia-du-tresor-repose-sur-la-detection-reponse-creant-un-deficit-de-prevention-de-plus-de-10-millions-de-dollars)

Pickup - [https://oestouro.com/noticias](https://oestouro.com/noticias/202602/337879-analise-revela-que-97-do-framework-de-ia-do-tesouro-baseia-se-em-detectar-e-responder-criando-lacuna-de-prevencao-de-mais-de-us-10-milhoes)

Pickup - [https://fishervista.com/en](https://fishervista.com/en/analysis-reveals-us-treasurys-ai-framework-relies-on-97-detect-a/202628621)

Pickup - [https://www.newsworthy.ai/curated](https://www.newsworthy.ai/curated/analysis-reveals-97-of-treasurys-ai-framework-relies-on-detect-a/202628621)

Pickup - [https://news.newswriter.ai/curated-news](https://news.newswriter.ai/curated-news/202602/396195-treasurys-ai-framework-relies-on-97-detect-and-response-leaving-financial-services-vulnerable-to-autonomous-agents)

Pickup - [https://news.trinzik.ai/frontier-tech-news](https://news.trinzik.ai/frontier-tech-news/202602/396218-vectorcertain-analysis-reveals-97-of-treasury-ai-framework-operates-in-detect-and-respond-mode-creating-10-million-prevention-gap)

Pickup - [https://news.tsigcommandsphere.com](https://news.tsigcommandsphere.com/news/202602/396228-analysis-reveals-97-of-financial-ai-framework-focuses-on-detection-creating-40-billion-prevention-gap)
 

 



![Blockchain Registration](https://cdn.newsramp.app/newsworthy/qrcode/262/24/divevLgu.webp)