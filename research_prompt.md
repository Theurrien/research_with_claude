# Research Workflow

## Phase 1: Rapid Discovery (Semantic Search First)
1. **Semantic Search**: Use semantic search with the research question to identify the most relevant papers immediately. This is your "prioritized search tool" - start here.
2. **Initial Review**: For the top 10-15 results, quickly check:
   - If they have notes (priority source)
   - If they have annotations
   - Abstract/metadata if no notes
3. **Document in Scratchpad**: Record key insights with paper links and item keys

## Phase 2: Systematic Collection Exploration
4. **Identify Relevant Collections**: Based on the question domain, identify 2-3 most relevant collections
5. **Extract Tags**: List all tags from papers in these collections and identify the most relevant ones for the question
6. **Gap Analysis**: Search for papers with identified tags that didn't appear in semantic search
7. **Check for Missed Insights**: Review notes and annotations from these additional papers
8. **Document**: Add findings to scratchpad with commentary on why these were missed in Phase 1

## Phase 3: Supplementary Sources
9. **Cross-Reference with Readwise**: Search Readwise library for additional perspectives
10. **Document**: Add any new insights to scratchpad

## Phase 4: Synthesis & Analysis
11. **Analyze Notes**: Review all documented insights in your scratchpad
12. **Construct Argument**: Write a reasoned, evidence-based response to the initial question
13. **Cite Sources**: Use APA 7 style throughout
14. **Add Bibliography**: Complete reference list at the end

# Tools
- Zotero
- Readwise
- File System for the .md file related to the scratchpad.


# Scratchpad Structure

Create a `.md` file with the File System MCP on the computer. Use the Write File function. Name the file after the research question with this structure:

```markdown
# Research Question
[User's question here]

# Research Process Log

## Phase 1: Semantic Search Discovery
### Search Query: "[your query]"
### Top Results:
- [Item Key] - [Title] - [Authors, Year]
  - **Notes**: [key insights from notes]
  - **Annotations**: [relevant highlights]
  - **Link**: [Zotero link]

## Phase 2: Collection & Tag Analysis
### Relevant Collections: [list]
### Key Tags: [list]
### Additional Papers Found:
[same structure as above]

### Gap Commentary:
<!-- Why didn't Phase 1 find these? Are they still relevant? -->

## Phase 3: Readwise Sources
[similar structure]

## Phase 4: Synthesis

### Key Themes Identified:
1. 
2. 
3. 

### Evidence Map:
[Theme 1]
- Paper A (item_key): finding X
- Paper B (item_key): finding Y

---

# Answer Draft
[Your reasoned argument will go here]
```

---

# Critical Guidelines

## Documentation Standards
- **Always include item keys** - essential for traceability
- **Use HTML comments** for your analytical thinking: `<!-- Why is this significant? -->`
- **Link everything** - make it easy to trace back to sources
- **Note gaps** - if Phase 1 missed something important, document why

## Search Strategy
- **Semantic search first** - Don't waste time on exhaustive lists before finding what's relevant
- **Tags as filters, not catalogs** - Use tags to refine, not to enumerate everything
- **Collection context** - Use collections to understand themes and find edge cases
- **Readwise for breadth** - Different types of sources might be there

## Fulltext Strategy (Use Sparingly)
**Context Window Risk**: Fulltext retrieval can consume tokens quickly. Use strategically.

### When to USE fulltext:
- **High-value, low-info papers** - Semantic search ranks it #1-3, but it has NO notes/annotations
- **Verification** - You've made a claim in Phase 4 synthesis and need to verify a specific detail
- **Filling critical gaps** - You have only 1-2 relevant papers and need more depth
- **Specific queries** - Looking for a particular methodology, framework, or definition
- **Quality over quantity** - Better to deeply read 2-3 key papers than shallowly scan 20

### When to AVOID fulltext:
- **Papers with good notes** - Your past self already did the synthesis
- **Early exploration** - Use annotations first, they're your highlights
- **Context window is filling up** - You're at 50%+ token usage
- **Papers ranked lower** - Focus fulltext on top 3-5 most relevant
- **Speculative browsing** - Don't fish with fulltext, use it strategically

### Application by Phase:
- **Phase 1**: Use fulltext ONLY for top 3 papers IF they lack notes/annotations
- **Phase 2**: Use fulltext for collection papers ONLY if they fill a critical gap
- **Phase 4**: Use fulltext for verification of specific claims before finalizing synthesis
- **Token Budget**: Stop using fulltext if context usage > 60% (monitor carefully)

## Quality Checks
- **Only use found information** - If library doesn't have relevant content, tell the user explicitly
- **Prefer notes over annotations** - Notes show your prior synthesis
- **Check abstracts last** - Only if no notes/annotations exist
- **Cite properly** - APA 7 style, complete bibliography

## Efficiency Principles
- **Fail fast** - If semantic search returns nothing relevant, check collections before giving up
- **Document decisions** - Why did you choose certain papers over others?
- **Stop when saturated** - If you're seeing repeated themes and no new insights, move to synthesis
- **Quality over quantity** - Better to deeply analyze 10 papers than shallowly scan 50

---

# File Location
Create the scratchpad file at: `/replace_with_your_path/[question_name].md`
Update it throughout the research process so it can serve as backup and documentation.
