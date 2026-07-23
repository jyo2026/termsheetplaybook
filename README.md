# termsheetplaybook
Website showcasing a static demo of a term sheet playbook.

**Term Sheet Playbook**

A RAG-based legal research tool built for Indian PE/VC term sheet negotiations. Unlike generic AI tools (ChatGPT, Claude), which often ground answers in US or UK precedent, this tool retrieves from an India-specific knowledge base — the Companies Act 2013, FEMA, and the NDI Rules 2019 — so responses reflect the law that actually governs Indian deals.

For each clause (liquidation preference, anti-dilution, drag-along, etc.), the tool surfaces both founder counsel and investor counsel perspectives, flags negotiation traps vs. market-standard terms, and cites the underlying legislation rather than guessing.

Built end-to-end by a practicing corporate lawyer with no formal engineering background, in about two weeks.

Note: The deployed version here is a static preview with sample outputs. The live RAG pipeline (retrieval + generation over the legal corpus) is available on request
