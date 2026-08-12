# Executive Summary

## Whitepaper Labs: Long-Horizon AI Memory Research

Whitepaper Labs explores how AI systems can retain, organize, and reactivate important state over long-running interactions and autonomous trajectories without treating memory as an undifferentiated archive.

The current research direction is **Metadata-Driven Memory Control for Long-Horizon AI Agents**. Its central hypothesis is that expensive semantic understanding should be concentrated around memory-state changes, while routine relevance management should operate on a smaller persistent control layer containing tags, weights, persistence rules, triggers, polling schedules, lifecycle state, provenance, and relations.

The repository currently covers three connected themes:

- **Polling-based contextual flagging** - allowing important state to become salient proactively rather than relying exclusively on passive similarity retrieval.
- **Memory management and layering** - separating persistent information by role and lifecycle instead of treating all stored context equally.
- **Metadata-driven memory control** - using a compact control plane to decide when full memory retrieval or semantic re-evaluation is warranted.

The latest paper is explicitly positioned against existing academic and practical memory systems. Claims about resource efficiency, recall, and long-horizon robustness are presented as research hypotheses and include a proposed evaluation framework rather than being stated as established empirical results.

**Author:** Marco Rapp, Independent Researcher. Research and drafting were assisted with ChatGPT by OpenAI and are disclosed as AI assistance rather than scientific co-authorship.
