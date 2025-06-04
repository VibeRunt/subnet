# VibeRunt Subnet: Executive Summary

## 1. Overview & Vision

**VibeRunt** is a proposed Bittensor Subnet designed to decentralize and incentivize the creation and curation of high-quality, subjectively appealing, and engaging **interactive digital artifacts**. Initially focusing on rich HTML (with embedded JS/CSS and assets), the Subnet aims to become a foundational "Taste & Refinement Layer" for a wide array of AI-generated creative outputs.

Our vision is to empower a new generation of creators by providing access to a competitive ecosystem of specialized AI "Taste Augmentors" (Miners) capable of transforming simple prompts into sophisticated interactive experiences. Simultaneously, VibeRunt offers GenAI model providers a platform to showcase and monetize their unique refinement capabilities. We believe that while raw generative power is becoming a commodity, the ability to imbue AI creations with nuanced "taste," compelling interactivity, and demonstrable engagement is where true value lies. VibeRunt aims to be the decentralized engine for this crucial "last mile" of creative AI.

This Subnet directly supports applications like **vhybZ** (a user-facing platform for effortless interactive artifact creation) by providing its core generative and refinement engine, while also offering its services via API to a broader ecosystem of creative tools and platforms.

## 2. Problem & Opportunity

Current AI generation often lacks the nuanced "taste," interactivity, and subjective appeal that truly captivates audiences. Creators struggle to translate ideas into polished, engaging interactive experiences without significant manual effort or specialized skills. Simultaneously, specialized GenAI providers capable of such refinement lack efficient channels to reach creators and monetize these niche capabilities.

The Bittensor ecosystem values subnets that:
*   Address clear niches and solve real problems in AI.
*   Foster decentralized competition and specialized "work."
*   Rely on (increasingly) objective and measurable benchmarking.
*   Offer practical utility and potential for broad ecosystem integration.

VibeRunt meets these criteria by tackling the subjective challenge of "good design" and "engaging interaction" in AI generation, aiming to codify and scale the curation of aesthetic and interactive quality.

## 3. The `$VIBE` Token Economy: A Robust Utility-Driven Model

The VibeRunt Subnet will be powered by its native utility token, **`$VIBE`**. The tokenomics are designed to create a sustainable, self-reinforcing ecosystem where demand is driven by utility and supply is incentivized by fair rewards for valuable contributions.

### 3.1. Demand Drivers for `$VIBE` (Why Acquire/Spend/Stake):

*   **Content Creators (via platforms like vhybZ):**
    *   **Pay-Per-Artifact Generation:** Primary demand sink. Creators spend `$VIBE` to generate and refine interactive artifacts. Costs can scale with complexity or the use of premium "Taste Augmentor" Miners. *Transparency in cost breakdown (which Miners/MCPs are used) is paramount.*
    *   **Staking for Access & Quotas:** Creators can stake `$VIBE` to receive discounted/free generation quotas, access to premium features, or faster processing. This model preserves creator capital while ensuring platform utility and reducing token velocity. A dedicated creator dashboard will provide full transparency on stake benefits and usage.
    *   **Engagement Boosting Services:** Spend `$VIBE` for platform features that enhance the visibility and virality potential of their generated artifacts (e.g., enhanced "showcase video" generation).
    *   **Monetization Features (Future):** Potential to use `$VIBE` to gate exclusive artifacts or pay small listing fees in a creator-to-creator asset marketplace within consuming applications.

*   **GenAI Providers (Miners - "Taste Augmentors"):**
    *   **Registration & Listing Stake:** Must stake `$VIBE` to operate as a Miner on the VibeRunt Subnet, signaling commitment and providing sybil resistance. Higher stakes could correlate with capacity or visibility.

*   **Validators ("Guild Leads"):**
    *   **Staking Requirement:** Must stake a significant amount of `$VIBE` to become a Validator, aligning their incentives with the Subnet's quality and integrity.

*   **End-Users / Token Holders (General Ecosystem Participants):**
    *   **Speculative Demand/Investment:** Desire for `$VIBE` appreciation as the ecosystem grows.
    *   **Staking for Yield:** Standard staking rewards from network emissions by delegating to Validators.
    *   **(Future) Platform Subscriptions:** Platforms like vhybZ consuming the Subnet's services may offer end-user subscriptions, a portion of which could be used to acquire `$VIBE` for ongoing Subnet interaction, creating indirect demand.

### 3.2. Supply & Distribution of `$VIBE` (How to Earn):

*   **Miners ("Taste Augmentors" / Prompt Engineers):**
    *   **Primary Earnings: Payment for Validated Generations:** Miners earn `$VIBE` each time their "Taste Augmentor" service successfully generates/refines an artifact that meets the quality and engagement criteria set by Validators. This is a direct payment for their specialized prompt engineering work.
    *   **Network Emissions:** Receive a share of ongoing `$VIBE` emissions, proportional to the quality and volume of their validated contributions.

*   **Validators ("Guild Leads" curating "Taster" feedback):**
    *   **Validation Rewards:** Earn `$VIBE` (from network emissions and potentially a share of transaction fees) for accurately:
        *   Managing their "Guild of Tasters."
        *   Aggregating and synthesizing subjective feedback.
        *   Applying "Taste Models" (once developed).
        *   Evaluating Miner outputs against defined benchmarks and achieving consensus.
    *   *Long-term income potential for early, high-quality human curators whose data shapes the foundational "Taste Models."*

*   **"Tasters" (within Validator Guilds - "Normal People"):**
    *   **Feedback-to-Earn:** Earn small amounts of `$VIBE` for providing high-quality, consistent subjective feedback on artifacts, contributing valuable data to the validation process.

*   **Stakers (Delegators to Validators):**
    *   Earn a share of Validator rewards through network emissions.

*   **Subnet Owners (Initial Development Team):**
    *   Receive the standard Bittensor percentage of `$VIBE` emissions for ongoing Subnet development, maintenance, and ecosystem growth.

### 3.3. Why this Token Economy is Robust & Ensures Longevity:

*   **Intrinsic Utility:** `$VIBE` is not just speculative; it's essential for the core function of the Subnet – creating interactive artifacts. Creators *need* it.
*   **Balanced Incentives:** All key actors (Creators, Miners, Validators, Tasters) have clear economic incentives to participate and contribute value.
*   **Demand Linked to Value:** As the quality and utility of artifacts generated by the Subnet increase (driven by Miner competition and Validator curation), more creators will demand `$VIBE`, increasing its value.
*   **Reduced Velocity through Staking:** Creator and Validator staking mechanisms lock up supply, promoting long-term alignment.
*   **Scalable Fallback for Virality:** The vhybZ platform can implement cheaper fallback models if a creator's staked `$VIBE` allowance for viewer interactions is exceeded, ensuring user experience while creating an upsell incentive for creators.
*   **Virtuous Cycle:** Better Miner "Taste Augmentors" ➜ Higher Quality Artifacts ➜ More Creator Demand for `$VIBE` ➜ Higher Rewards for Miners/Validators ➜ Attracts More/Better Miners & Validators ➜ Further Quality Improvement.

## 4. VibeRunt Subnet Mechanism: For the Bittensor Nerd

This section details the technical and operational aspects aligning with Bittensor's core principles.

### 4.1. Miner Role: Specialized "Taste Augmentors"

*   **Core Function:** Miners are sophisticated **Prompt Engineers** who operate "Taste Augmentor" services. They do not necessarily train foundational models from scratch. Instead, they develop and host specialized layers (meta-prompts, intent refinement engines, style libraries, session-aware logic) that work *on top of* existing foundation models (e.g., Gemini, Claude, open-source VLMs/LLMs relevant to the artifact type).
*   **Input/Output:**
    *   **Input (from vhybZ platform or other consuming apps, via a standardized Synapse):** User's raw prompt, a unique `Session ID` (allowing Miners to maintain conversational state/memory for iterative refinement), target `Model ID` (specifying constraints or desired output characteristics like style profile, artifact type – initially HTML). Optional attachments for reference.
    *   **Output:** The final generated interactive artifact (e.g., HTML/JS/CSS package) ready for validation. (The "augmented prompt" is an internal step for the Miner).
*   **Onboarding & Deployment:**
    *   **Easy Onboarding:** Template GitHub repositories will be provided for "Taste Augmentor" services. A "one-click deploy" option will instantiate a managed MCP server for new Miners, who primarily focus on the prompt engineering logic via a web UI. They stake `$VIBE` to cover their node server costs.
    *   **Advanced Deployment:** Sophisticated Miners can deploy their own custom MCP servers, allowing full control over their model stack and composition logic.
*   **Competition:** Miners compete to produce artifacts that best match the task requirements and score highest on subjective "taste" and engagement metrics defined by Validators. Specialization in artifact types (HTML initially), styles, or interactive complexity is encouraged.

### 4.2. Validator Role: Two-Tiered "Validator Guilds"

Validators are crucial for navigating the subjectivity of creative output.

*   **Tier 1: "Tasters" (Community Curators):**
    *   "Normal people" who join specialized "Guilds" (e.g., "Boomer UI Guild," "Minimalist Design Guild," "Educational Games Guild").
    *   They interact with Miner-generated artifacts and provide structured subjective feedback (ratings, comments, interaction data).
    *   Incentivized with small `$VIBE` rewards for quality feedback.

*   **Tier 2: "Guild Leads" (Registered Subnet Validators):**
    *   Stake `$VIBE` to operate.
    *   Manage their Taster Guild, define artifact review tasks for their Guild.
    *   **Synthesize Taster Feedback:** Aggregate quantitative and qualitative data from their Guild.
    *   **Develop & Utilize "Taste Models":** Over time, use Guild feedback to train/fine-tune AI models ("Taste Models") that can predict human aesthetic/engagement preferences for specific styles/artifact types. These models assist in scaling evaluation.
    *   **Incorporate Objective Metrics:** Combine subjective Guild feedback and Taste Model scores with objective metrics (e.g., code validity, performance scores from sandboxed rendering, accessibility checks for HTML).
    *   **Submit Consolidated Scores:** Provide a final score for Miner outputs to the Bittensor network for consensus and reward distribution.
*   **Benchmark & Criteria Transparency:** All benchmark tasks and high-level evaluation rubrics will be public. Detailed methodologies of Guild Leads will also be transparent.

### 4.3. Task Lifecycle & Evaluation Pipeline (Example for HTML Artifacts):

1.  **Task Issuance:** vhybZ (or another app) sends a task to the Subnet (user prompt, session ID, style profile ID).
2.  **Miner Response:** Relevant Miners process the task with their "Taste Augmentors" and submit the HTML artifact.
3.  **Validation Process:**
    *   **Sandboxed Rendering & Interaction:** Artifacts are rendered in a secure environment. Automated tests check basic functionality, performance (e.g., Lighthouse), and accessibility.
    *   **Taster Guild Evaluation:** Artifacts are distributed to Tasters in relevant Guilds for interaction and subjective feedback.
    *   **Taste Model Scoring (Phase 2+):** AI Taste Models provide scores based on learned preferences.
    *   **Guild Lead Synthesis:** The Validator aggregates all data points into a final score.
4.  **Consensus & Reward:** Scores are submitted, consensus is reached, and `$VIBE` is distributed.

### 4.4. Synapse Schema (Conceptual for HTML):

```python
class InteractiveArtifactSynapse(bt.Synapse):
    # Inputs from Requesting Application
    user_prompt: str
    session_id: str # For Miner to maintain stateful context
    target_style_profile_id: Optional[str] = None # e.g., "corporate-clean-v1"
    target_artifact_type: str = "html_interactive" # Initially HTML, extensible
    reference_attachments: Optional[List[bytes]] = None # e.g., images for style

    # Output from Miner
    generated_artifact_bundle: Optional[bytes] = None # e.g., zip of HTML, JS, CSS, assets
    miner_confidence_score: Optional[float] = None
    errors: Optional[List[str]] = None
```

### 4.5. Anti-Gaming & Fair Competition:

*   Randomized task distribution to Miners.
*   Sophisticated similarity checks on submitted artifacts to detect plagiarism or trivial variations.
*   Reputation systems for Miners and Validators based on historical performance and accuracy.
*   Validator Guild diversity to prevent monoculture of taste.
*   Regular updates to benchmarks and Taste Models.

## 5. Future Directions & Wider Utility

While vhybZ (the app for interactive HTML artifacts) will be the flagship consumer of the VibeRunt Subnet, the Subnet's architecture is designed for broader applicability:

*   **Support for Diverse Artifact Types:** The "Taste Augmentor" and "Validator Guild" model can be extended to other generative modalities (e.g., 3D models like STL, interactive audio, short-form video styles) by onboarding Miners and Validators specialized in those areas.
*   **API Access for Third-Party Platforms:** Other creative tools, no-code platforms, game engines, or educational apps can integrate with VibeRunt via API, paying `$VIBE` to access its decentralized network of "Taste Augmentors."
*   **Decentralized Marketplace for "Taste Augmentor" Profiles:** Highly successful Miner "Taste Augmentor" configurations could potentially be licensed or sold.
*   **Feedback Data Economy:** Anonymized, aggregated interaction data from artifacts could become a valuable resource for training more general AI models (with appropriate privacy safeguards and potential compensation).

## 6. Conclusion

VibeRunt aims to be a pioneering Bittensor Subnet that tackles the complex challenge of subjective quality in AI generation. By fostering a competitive ecosystem of specialized "Taste Augmentor" Miners and curated "Validator Guilds," we can create a powerful engine for producing truly engaging and aesthetically refined interactive digital artifacts. The `$VIBE` tokenomics are designed to fuel this ecosystem, ensuring robust utility, aligned incentives, and long-term value accrual as the network grows and diversifies its creative output.
