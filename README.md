# Research Assistant with LangGraph

This project is a Python-based research paper generation assistant that leverages LangGraph, LangChain, and OpenAI's GPT models to automate the creation of structured research papers. It is designed to support students, researchers, and professionals in quickly generating well-organized academic documents with citations and references.

The system combines AI-driven text generation with real-time academic literature search from Google Scholar and Semantic Scholar to produce research sections that are coherent, well-cited, and formatted in Markdown. Users can provide human feedback at each stage to refine the content before moving on to the next section.

 Features
 Automated Section Generation: Generates research paper sections including Introduction, Literature Review, Methodology, Results, and Conclusion.
 Academic Paper Search: Integrates with Google Scholar and Semantic Scholar to extract abstracts, authors, publication year, and links for citation purposes.
 Structured Output: Produces clean, structured Markdown output for each section.
 Human-in-the-loop Feedback: Allows iterative refinement through human feedback after each section.
 References Management: Automatically formats references in APA style using the sources retrieved during the search.
  File Export: Generates a single Markdown file containing the complete research paper.

How It Works
1. Topic Input: The user provides a research topic.
2. Introduction Generation: The AI generates an introduction, defining the research problem and outlining the structure.
3. Literature Review: Searches academic papers relevant to the topic, extracts abstracts and metadata, and writes a structured literature review.
4. Methodology Section: Generates a methodology based on standard research methods and findings from previous papers.
5. Results Section: Synthesizes findings from academic sources and presents them in a clear format.
6. Conclusion: Summarizes insights, implications, and recommendations.
7. Output: All sections are combined and saved into a text file (research_paper_output.txt).



 Clone the repository:
   ```bash
   git clone https://github.com/Khadijah911/research_assistant.git
