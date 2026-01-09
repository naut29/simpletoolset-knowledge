# Export verification report

Generated at: 2026-01-09T01:57:10.338Z

## Counts
- Tools: 59
- Categories: 8
- Use cases: 25

## Checks performed
- Frontmatter present: PASS
- Canonical present: PASS
- Canonical uniqueness: PASS
- tools.json coverage: PASS
- Sitemap coverage: 92 entries

## Notes
- Sitemap <-> Canonical consistency: all 92 canonicals present in sitemap with a 1:1 match; no duplicates detected.
- Duplicate-rate heuristic (descriptions + overview sentences): 16.6% before, 0.0% after (177 sentences).
- Internal links verified as relative; canonical uniqueness check: PASS.
- Use cases expanded from 5 to 25 in public-knowledge and re-exported.
- Added `llms.txt` and `ai-index.md` for AI/LLM indexing guidance.
- Missing frontmatter: none
- Missing canonical: none
- Duplicate canonicals: none
- Tools missing from tools.json: none

## Spot-check QA
- Sample: 10 tools (5 from `public-knowledge/tools`, 5 from `public-knowledge-export/knowledge/tools`), 3 categories (2 + 1), 3 use-cases (2 + 1).
- Canonical pattern: all sampled files match `https://simpletoolset.com/en/...` and expected prefixes (tools use category/tool_slug; categories and use-cases match filename).
- Description length: all sampled descriptions are within 140-170 characters.
- Suspicious claim keywords to review:
  - `public-knowledge/tools/favicon-generator.md`: "Upload a square source image..." and "What image should I upload?: ..."
  - `public-knowledge-export/knowledge/tools/password-generator.md`: "protect your accounts..." and "change my passwords... each account ..."
  - `public-knowledge/categories/design-tools.md`: "no signup required..."
  - `public-knowledge-export/knowledge/categories/design-tools.md`: "no signup required..."
  - `public-knowledge/use-cases/compress-images-for-web.md`: "Upload the image..."
  - `public-knowledge-export/knowledge/use-cases/merge-split-rotate-pdf-files.md`: "easier to upload..." and "Do these tools upload my PDFs?: ..."
- Internal links: no missing .md targets found in sampled files.
