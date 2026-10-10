# Looseleaf Workbench — Agent Instructions

This is a staging area for research arising from inquiries already under way. A note here will be promoted to the main looseleaf collection when the literature search is complete, all sources have been acquired, all sources the note relies on have an accurate source note, and a note has been carefully reviewed.

## Capturing research

When asked to create an entry, preserve the valuable intellectual substance of the inquiry: the motivating question and framing, important discoveries, distinctions, arguments, evidence, objections, uncertainties, and promising directions. Produce a coherent, independently readable note rather than copying a chat response or turning it into a generic literature review.

Let the material determine the structure, length, and headings. There are no required templates, tags, or frontmatter.

Place entries in `entries/<descriptive-name>.md`. An entry typically has source-specific supporting notes for any sources it relies on. These belong in `sources/<entry-name>/<BibTeX-key-with-colons-removed>`. Use relative links. Check existing entries before creating duplicates.


## Research and revision

Use **Research / Personal Papers** for bibliographic records and original full texts. Use **Exa**, **Parallel Search**, your own search tools, citation chasing, and other appropriate resources to discover sources and evaluate coverage.

Reconsider source selection as well as the accuracy of individual claims. Search prominence, open access, and convenient availability are poor substitutes for relevance and evidential quality. As a general rule, avoid relying on research in low-quality journals like Frontiers. Also avoid unpublished research such as talks.

Follow the user's `cite-published-source` skill when available. Use verified BibTeX keys in `\citet{...}` and `\citep{...}` whenever known; never invent keys. For sources absent from the library, record full bibliographic details and a copyable DOI (or, if no DOI available, a suitable metadata link).

Keep records of what sources were actually read and checked in `sources/<entry-name>/checklist.md`. This file should serve as both a record of what has been read and a list of sources that may still need to be acquired or read. 

After investigating sources, reconsider the main account rather than merely adding references.

## Provenance and promotion

Use Git commits to record meaningful changes and their reasons. Identify the agent and model where possible.

Entries may eventually be promoted to `looseleaf`, normally together with their supporting source notes. Once promotion has succeeded, remove the promoted material from the workbench's active tree. Its development history remains in Git.