# Looseleaf Workbench — Agent Instructions

This is a staging area for research arising from inquiries already under way. Promotion to the main Looseleaf collection is appropriate when the literature search is sufficiently comprehensive for the question and supported conclusions, significant gaps are identified, every publication substantively relied on has a verified BibTeX key and an accurate source note checked against the original full text, and the entry has been carefully reviewed.

## Capturing research

When asked to create an entry, preserve the valuable intellectual substance of the inquiry: the motivating question and framing, important discoveries, distinctions, arguments, evidence, objections, uncertainties, and promising directions. Produce a coherent, independently readable note rather than copying a chat response or turning it into a generic literature review.

Let the material determine the structure, length, and headings. There are no required templates, tags, or frontmatter.

Place entries in `entries/<descriptive-name>.md`. Source-specific notes belong in `sources/<entry-name>/<BibTeX-key-with-colons-removed>.md` (e.g. `setiya:2016_practical` becomes `setiya2016_practical.md`). Never invent a BibTeX key or create a publication source note before its verified key exists and the original full text has been consulted. Non-substantive corrections and warnings to existing notes do not require renewed full-text access. Use relative links. Check existing entries before creating duplicates.

Initial capture can precede source checking; mark uncertainties candidly and track missing or unchecked sources in the checklist rather than making premature source notes.

For each inquiry, maintain only its main entry, a source checklist, and source-specific notes (one per publication). Do not create separate plans, progress reports, alternative drafts, or other working documents. Revise the existing files; Git preserves their previous versions.

Inline annotations are temporary working comments. Interpret the first non-whitespace character of a comment: `∞` is Stephen-owned—never act on, edit, remove, or resolve it without explicit instruction; `^` addresses agents; unmarked comments are agent-addressed unless clearly personal. Put lasting conclusions in the prose. Remove small agent comments once resolved; for larger actions awaiting review, preserve the request, mark it `[done]`, and add a brief italic reply. Preserve `∞` annotations through revision and promotion.

## Research and revision

Use **Research / Personal Papers** for bibliographic records and original full texts. Use **Exa**, **Parallel Search**, your own search tools, citation chasing, and other appropriate resources to discover sources and evaluate coverage.

Reconsider source selection as well as the accuracy of individual claims. Search prominence, open access, and convenient availability are poor substitutes for relevance and evidential quality. Be especially critical of research in less selective journals, including Frontiers titles, without prejudging individual papers. Treat unpublished research cautiously and distinguish it clearly from published evidence.

Follow the user's `cite-published-source` skill when available. Use verified BibTeX keys in `\citet{...}` and `\citep{...}` whenever known; never invent keys. For sources absent from the library, use author–date references and record full bibliographic details and a copyable DOI (or, if no DOI is available, a suitable metadata link) in the checklist until a verified library key is available.

Keep records of what sources were actually read and checked in `sources/<entry-name>/checklist.md`. It should also track sources needing acquisition, library keys, or further checking; it is a process record, not a substitute for source notes.

Source notes should establish what the original publication actually argues or reports, what evidence it provides, what it fails to establish, and how it bears on the inquiry. Include precise locators where possible and an honest record of the material accessed and checks performed. Original full text is required to create or substantively revise a source assessment; non-substantive corrections and warnings may be made without it. Do not present abstract-level access as full-text verification.

After investigating sources, reconsider the main account rather than merely adding references.

## Provenance and promotion

Use Git commits to record meaningful changes and their reasons. Identify the agent and model where possible.

Promote an entry only when explicitly requested by the user. Transfer the main entry and its checked source notes to looseleaf, recording the originating workbench commit. Verify that the transferred files and links are correct before removing the promoted entry, its checklist, and its source notes from the workbench's active tree. Git preserves the development history.