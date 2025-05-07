Prompt: Create a mind map from the sources. List topics as central ideas, main branches, and sub-branches. Output it in Markdown format.

# **NotebookLM for SEO Research**

## **Core Functionality: Discover Source**
*   Built-in web search feature.
*   Describe a topic with details.
*   Scans hundreds of online sources.
*   Returns up to 10 most relevant results with a blurb.
*   Import selected results as sources.
*   Usually returns authoritative sources (big brands, reputable media, academic institutions, high-view YouTube videos).
*   Seldom returns niche or personal sites unless the topic is very niche.
*   Powered partly by Google's algorithm, results likely ranked on page one or two.
*   Can interpret search operators (`site:`, `filetype:`, `daterange:`).
    *   Handy for granular control.
*   Tips for better results:
    *   Be more specific with topic description (e.g., "B2B marketing strategies, targeting small startup").
    *   Narrow scope by specifying time range (e.g., "recent three months," "past two years").
    *   Specify source type (e.g., "PDF reports," "YouTube videos," "blog articles").
    *   Ask for diverse sources.
*   Always review sources before importing; irrelevant results can occur.
*   Double-check for overlapping sources.

## **SEO Use Cases**

### **Competitor Content Gap Analysis**
*   Compares competitor's content.
*   Identifies competitor content strategies.
*   Use Discover Source to scan competitor domains/content.
*   Use search operators (`site:`, `day range`, `keyword`) for specific content.
*   Import relevant sources.
*   Use prompts to identify gaps.
    *   Breakdown by customer journey stages.
    *   Focus on target audience role.
    *   Focus on problems addressed.
*   Summarises content opportunity analysis.
*   Output: Analysis by stages, audience differences, problem focus, potential new content to explore.
*   Helps quickly estimate strategy differences and know content to prioritise.

### **Generating Better FAQs for AI Search**
*   Q&A format is favoured by AI search engines.
*   NotebookLM has a built-in FAQ feature, but it may not be in-depth.
*   Use Discover Source to find question-based content from forums (Reddit, popular forums).
    *   Can include basic and advanced questions.
*   Import own research sources (e.g., search console data, Ahrefs list).
*   Can copy and paste data (e.g., from CSV) as text if direct file upload isn't supported.
*   Use prompts to identify valuable questions (e.g., top 20) and group by search intent.
    *   Specifying "FAQ page" ensures bite-sized Q&A.
*   Output: Good questions and answers, often grouped by search intent (e.g., "getting started," "music reading and theory").
*   More in-depth and specific than built-in feature.
*   Can pick questions to combine into articles/guides.
*   Add own insights to improve information gain for AI search.

### **Getting Authority Signals for AI Search/EEAT**
*   AI evaluates authority signals to identify resources to trust, cite, and prioritise.
*   Use Discover Source to find web pages from authoritative sources.
*   Import top-ranked pages.
    *   Can use Chrome plugins like SERP Snippet Extractor and WebSync full site importer for bulk import.
    *   WebSync imports URLs (pages or entire websites).
*   Use prompts to create a list of identified authority signals.
    *   Signals include: author's expertise/credentials, practical tips, inclusion of research data, examples.
*   Save signals list as a note.
*   Use secondary prompts to drill into specific details.
    *   Details include: common citation patterns, specific data points, credentials mentioned, reference sources.
*   Provides insights on how top pages leverage signals.
*   Helps understand what signals to include or enhance in your content.

### **Semantic Keyword Clustering**
*   Important for AI search (understanding context and meaning).
*   Streamlines the process and provides quick ideas on keyword groups.
*   Use Discover Source to find sources on a topic (e.g., "leadership in AI Age").
    *   Explicitly mention diverse sources (blog, practical guides, tutorials, case studies).
*   Generate a **mind map** (visual tool).
    *   Helps understand topic hierarchy and core subtopics.
    *   Assists in planning content and building topical authority.
    *   Nodes can trigger prompts.
    *   Can be downloaded as an image.
*   Use prompts to create semantic clusters.
    *   Breaks down into primary topics and subtopics.
    *   Shows logical hierarchy and semantic terms that should be grouped.
*   Useful when expanding on subtopics.
*   Proposes a topic pillar structure.
*   Described as a more in-depth version of the generated mind map.
*   Includes a list of questions for content planning.

### **Keyword Gaps**
*   Helps spot missing keywords compared to competitors.
*   Improves content relevance.
*   Use Discover Source to find top content on a topic.
*   Import top-ranked pages using a plugin.
*   Use prompts to identify top keywords across sources (e.g., top 30).
    *   Includes keywords from top-ranked pages.
*   Use prompts to pull long-tail keywords.
*   Import your own article.
*   Use prompts to compare and find missing keywords in your article.
*   Identifies search intent that your article hasn't fully addressed.
*   Output: List of missing keywords, list of missing search intents.
*   Helps know important keywords and search problems to address to improve content depth.
*   Always review suggestions carefully.

### **YouTube Content Research & Key Insights**
*   YouTube video import is a very handy import feature.
*   Can do YouTube research for extra insights for content planning.
*   Use Discover Source for bulk video uploads.
*   Extract key insights, data claims, and supporting information.
*   Minimal hallucination helps minimise returning wrong information compared to some other tools.
