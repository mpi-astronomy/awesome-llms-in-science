# Awesome AI for Scientific Research [![awesome][awesome-badge]][awesome-link]

An [awesome list](https://github.com/sindresorhus/awesome) of resources for scientists wondering how to use LLMs in their research.  *Everyone* is invited to [contribute](CONTRIBUTING.md) by pull request.

## Table of Contents

- [Policies](#policies)
- [Acknowledgement](#acknowledgement)
- [Reproducibility](#reproducibility)
- [AI Risk and Ethics](#ai-risk-and-ethics)
- [Copyright & Legal Issues](#copyright--legal-issues)
- [Papers](#papers)
- [Other Awesome Lists](#other-awesome-lists)
- [Contribute](#contribute)
- [License](#license)

## Policies & Editorial Guidance

- **[AAS Journals](https://baas.aas.org/pub/2023i016)** – Editorial establishing that authors bear sole responsibility for manuscript content and that LLMs should be cited as software rather than listed as authors.

- **[COPE – Committee on Publication Ethics](https://publicationethics.org/cope-position-statements/ai-author)** – 2023 position statement clarifying that AI tools cannot meet authorship criteria because they cannot take responsibility for submitted work. Recommends transparency and disclosure.

- **[ICMJE – International Committee of Medical Journal Editors](https://www.icmje.org/recommendations/)** – Updated recommendations stating that AI-generated text does not qualify for authorship and that authors must disclose AI use and take responsibility for AI-assisted content.

- **[Nature Portfolio AI Editorial Policy](https://www.nature.com/nature-portfolio/editorial-policies/ai)** – Requires disclosure of AI use in Methods or Acknowledgments sections. AI tools cannot be credited as authors across all Nature journals.

- **[Science (AAAS) Editorial Policies](https://www.science.org/content/page/science-journals-editorial-policies)** – Prohibits AI-generated text, figures, or images without explicit disclosure and editorial approval. AI cannot be listed as an author.

- **[arXiv Submission Agreement](https://info.arxiv.org/help/policies/submission_agreement.html)** – Requires a human author to take full responsibility for submissions. AI-assisted content is allowed but must comply with arXiv policies.

- **[JOSS – Journal of Open Source Software AI Policy](https://joss.readthedocs.io/en/latest/submitting.html)** – Requires granular disclosure of AI use, including tools used, locations of use (code, paper, docs), and the scope of assistance. Human authors must review all outputs, and AI cannot participate in author–reviewer discussions.

- **[JWST / STScI Policy on Generative AI in Proposals](https://jwst-docs.stsci.edu/jwst-opportunities-and-policies/jwst-call-for-proposals-for-cycle-5/jwst-new-and-important-features)** – Allows generative AI use but requires explicit citation of AI-derived content (tool name, version, date, and usage description). Failure to disclose results in proposal disqualification.

- **[Deutsche Forschungsgemeinschaft (DFG) – Generative Models Guidelines](https://www.dfg.de/en/research-funding/principles-rules-good-practice/good-scientific-practice/guidelines-generative-models)** – Core German research integrity framework emphasizing transparency, documentation, and responsibility in research. Allows AI in grant proposals if disclosed and states AI use is evaluated “neither positive nor negative.” Prohibits AI use in preparing reviews.

- **[European Commission – Responsible Use of Generative AI in Research](https://research-and-innovation.ec.europa.eu/document/2b6cf7e5-36ac-41cb-aab5-0d32050143dc_en)** – Living guidelines defining when AI use in research (e.g., literature review, hypothesis development) counts as “substantial use” requiring disclosure.

- **[OWID / Frisch FAQ on AI and Research Integrity](https://ombudsgremium.de/13262/faq-artificial-intelligence-and-research-integrity/?lang=en)** – Continuously updated overview of AI policies across publishers, funding agencies, peer review practices, copyright, and detection tools. ⭐ an excellent FAQ with relevant resources ⭐

- **[Elsevier – Generative AI Policies for Journals](https://www.elsevier.com/de-de/about/policies-and-standards/generative-ai-policies-for-journals)** – Publisher policy requiring disclosure of AI use and prohibiting AI authorship.

- **[Taylor & Francis – Artificial Intelligence Policy](https://taylorandfrancis.com/our-policies/ai-policy/)** – Publisher policy addressing AI authorship, disclosure requirements, and restrictions on AI-generated content.

- **[Wiley – Artificial Intelligence Guidelines for Book Authors](https://www.wiley.com/en-us/publish/book/resources/ai-guidelines/)** – Detailed publisher guidance describing acceptable and prohibited uses of generative AI in scholarly books.

- **[Frontiers – Artificial Intelligence: Fair Use and Disclosure Policy](https://www.frontiersin.org/guidelines/policies-and-publication-ethics)** – One of the few publisher policies explicitly allowing AI-generated images if their use is disclosed.


## Acknowledgement

- **[Artificial Intelligence Disclosure (AID) Framework](https://crln.acrl.org/index.php/crlnews/article/view/26548)** – Framework proposing structured disclosure of AI use across research stages, inspired by the Contributor Roles Taxonomy (CRediT).

- **[AI Attribution Toolkit](https://aiattribution.github.io/)** – Attribution system inspired by Creative Commons licensing that allows authors to specify the proportion and role of AI contributions.

- **[American Psychological Association (APA) – How to Cite Generative AI](https://apastyle.apa.org/blog/cite-generative-ai-references)** – Citation guidance for referencing generative AI outputs in scholarly writing.

- **[Chicago Manual of Style – Citing AI-Generated Content](https://www.chicagomanualofstyle.org/qanda/data/faq/topics/Documentation/faq0422.html)** – Style guide recommendations for documenting AI-generated material in academic publications.

- **[Modern Language Association (MLA) – Citing Generative Artificial Intelligence](https://style.mla.org/citing-generative-ai-updated-revised/)** – MLA citation guidance for acknowledging AI-assisted writing.

- **[Berlin Universities Publishing – Guideline for Dealing with Artificial Intelligence](https://www.berlin-universities-publishing.de/en/ueber-uns/policies/ki-leitlinie/index.html)** – Institutional policy with recommendations on disclosure and citation of AI tools in scholarly publications.

## Reproducibility

### Standards & Principles

- **[FAIR Principles for Research Software (FAIR4RS)](https://www.nature.com/articles/s41597-022-01710-x)** – Extension of the FAIR data principles specifically for research software, emphasizing discoverability, accessibility, interoperability, and reuse of scientific code.

- **[Software Citation Principles](https://doi.org/10.7717/peerj-cs.86)** – Community consensus principles developed by FORCE11 recommending that research software be treated as a first-class scholarly output with persistent identifiers and formal citations.

### Journal & Publishing Policies

- **[AAS Journals – Software Citation Guidance](https://journals.aas.org/software-citation/)** – American Astronomical Society (2020). Policy recommending formal citation of research software and encouraging public code repositories with versioning and DOIs.

- **[Nature Research – Code Policy](https://www.nature.com/nature-portfolio/editorial-policies/reporting-standards#availability-of-computer-code)** – Nature Portfolio (2018). Editorial policy that custom code needed to reproduce results be made available to editors and reviewers upon request. Encourages code availability and provides recommendations for best code publication practices.

- **[Science Journals – Code and Data Availability Policy](https://www.science.org/content/page/science-journals-editorial-policies#research-standards)** – American Association for the Advancement of Science (AAAS) (2021). Access to custom code necessary to reproduce published results should be made available upon publication.

- **[Journal of Open Source Software (JOSS)](https://joss.theoj.org/)** –  A peer-reviewed journal where research software itself is the primary scholarly output and is reviewed for usability, documentation, and reproducibility.

- **[PLOS Open Science Policies](https://plos.org/open-science-policies/)** – Publisher-wide policies promoting transparency and reproducibility, including requirements or encouragement for sharing data, code, and other research artifacts associated with publications.

- **[PLOS Biology – Code Sharing Guidance](https://journals.plos.org/plosbiology/s/code-sharing-guidance)** – Editorial guidance stating that code underlying published results must be made publicly available upon publication. 

### Best Practices for Reproducible Workflows

- **[Best Practices for Scientific Computing](https://doi.org/10.1371/journal.pbio.1001745)** – Wilson et al. (2014). Influential guide describing core software practices for research, including version control, modular code, automated testing, and documentation.

- **[The Turing Way – A Handbook for Reproducible Data Science](https://book.the-turing-way.org/)** – The Turing Way Community (2019–present). Community-driven guide covering reproducible research practices including version control, documentation, environment capture, and open collaboration.

- **[Ten Simple Rules for Reproducible Computational Research](https://doi.org/10.1371/journal.pcbi.1003285)** – Sandve et al. (2013). Widely cited set of recommendations for ensuring computational reproducibility, including sharing code, recording dependencies, and automating workflows.

- **[Ten Simple Rules for the Open Development of Scientific Software](https://doi.org/10.1371/journal.pcbi.1002802)** – Prlić & Procter (2012). Guidelines for collaborative and transparent development of scientific software.

- **[Ten Simple Rules for the Care and Feeding of Scientific Data](https://arxiv.org/abs/1401.2134)** – Goodman et al. (2014). Practical guidelines for managing, documenting, and publishing research data to ensure reuse, reproducibility, and proper attribution.

## Infrastructure for Publishing Code

- **[Zenodo – GitHub Integration for Software Archiving](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content)** – European Organization for Nuclear Research (CERN) / OpenAIRE (2014–present). Service that archives GitHub releases and assigns DOIs for citation of research software.

- **[Software Heritage](https://www.softwareheritage.org/)** – Long-term archival infrastructure designed to preserve all publicly available source code and provide persistent identifiers.

- **[Astrophysics Source Code Library (ASCL)](https://ascl.net/)** – Registry of research codes used in astronomy that enables software indexing, citation, and discoverability in the literature.

## AI Risk and Ethics

- **[AI Risk Repository](https://doi.org/10.48550/arXiv.2408.12622)** – Comprehensive meta-review and taxonomy cataloguing risks associated with artificial intelligence systems.

## Copyright & Legal Issues

- **[German Publishers and Booksellers Association – Generative Artificial Intelligence FAQ](https://www.boersenverein.de/beratung-service/recht/kuenstliche-intelligenz/)** – Overview of copyright and publishing law issues related to generative AI.

- **[Creative Commons – Understanding CC Licenses and Artificial Intelligence Training](https://creativecommons.org/2025/05/15/understanding-cc-licenses-and-ai-training-a-legal-primer/)** – Legal overview explaining how Creative Commons licenses apply to the use of datasets in AI model training.

- **[European Union Artificial Intelligence Act (EU AI Act)](https://artificialintelligenceact.eu/the-act/)** – European regulatory framework governing development, deployment, and risk classification of artificial intelligence systems.

## Papers

- **[Buck et al. (2026) – AI-Assisted Scientific Assessment: A Case Study on Climate Change](https://arxiv.org/abs/2602.09723)** – Controlled case study of AI-assisted scientific assessment in climate science demonstrating both productivity gains and the limits of AI (“What” vs. “So What”).

- **[Fouesneau et al. (2024) – What is the Role of Large Language Models in the Evolution of Astronomy Research?](https://ui.adsabs.harvard.edu/abs/2024arXiv240920252F)** – Empirical study of 13 astronomers at MPIA using LLMs across research tasks, including a survey of usage patterns, benefits, failure modes, and recommendations.

- **[Hogg (2026) – Why Do We Do Astrophysics?](https://ui.adsabs.harvard.edu/abs/2026arXiv260210181H)** – Philosophical argument that astrophysics requires human responsibility, trust, and career stakes that AI cannot provide, framing the generation–verification asymmetry.

- **[Hosseini & Horbach (2023) – Fighting Reviewer Fatigue or Amplifying Bias?](https://doi.org/10.1186/s41073-023-00133-5)** – Analysis of risks of using LLMs in scholarly peer review, arguing that review shapes epistemic communities and normative frameworks in ways that cannot be outsourced to AI.

- **[Hyk et al. (2025) – From Queries to Criteria: Understanding How Astronomers Evaluate LLMs](https://arxiv.org/abs/2507.15715)** – Empirical study based on 368 queries and interviews with astronomers evaluating an LLM-based literature tool, revealing implicit evaluation criteria and benchmark recommendations.

- **[Lepp & Smith (2025) – “You Cannot Sound Like GPT”: Signs of Language Discrimination in Computer Science Publishing](https://doi.org/10.1145/3715275.3732202)** – Analysis of ~80,000 peer reviews showing persistent bias against non-native English authors and evidence that “ChatGPT-style” writing is used as a demographic marker.

- **[Liao et al. (2024) – LLMs as Research Tools: A Large-Scale Survey of Researchers’ Usage and Perceptions](https://arxiv.org/abs/2411.05025)** – Survey of 816 researchers across disciplines showing higher adoption and perceived benefit among traditionally disadvantaged groups.

- **[Messeri & Crockett (2024) – Artificial Intelligence and Illusions of Understanding in Scientific Research](https://doi.org/10.1038/s41586-024-07146-0)** – Nature Perspective introducing a taxonomy of AI visions in science (Oracle, Surrogate, Quant, Arbiter) and highlighting epistemic risks such as “illusions of understanding” and scientific monocultures.

- **[Mohammadi et al. (2026) – Is Generative AI Reshaping Academic Practices Worldwide?](https://doi.org/10.1016/j.ipm.2025.104350)** – Survey across 20 countries documenting adoption rates, demographic differences, and key concerns such as inaccuracy, plagiarism, and reduced critical thinking.

- **[Ren et al. (2025) – Towards Scientific Intelligence: A Survey of LLM-based Scientific Agents](https://arxiv.org/abs/2503.24047)** – Survey of 120+ LLM-based scientific agents covering architectures, benchmarks, and applications across scientific domains including astronomy.

- **[Song et al. (2026) – Large Language Model Reasoning Failures](https://arxiv.org/abs/2602.06176)** – Comprehensive survey categorizing reasoning failures in LLMs, distinguishing architectural limitations, application-specific failures, and robustness issues.

- **[Ting (2025) – Artificial Intelligence Compels the Astronomy Community to Rethink Research Identity](https://doi.org/10.1038/s41550-025-02510-0)** – Nature Astronomy World View arguing that LLMs force the astronomy community to reconsider metrics of merit, research identity, and education.

- **[Ting, Curtis-Trudel & Yao (2026) – What Understanding Means in AI-Laden Astronomy](https://arxiv.org/abs/2601.10038)** – Epistemological analysis distinguishing problem-solving (where AI excels) from problem-finding (where it does not).

- **[Trotta (2026) – The Indiscriminate Adoption of AI Threatens the Foundations of Academia](https://doi.org/10.1038/s41550-025-02738-w)** – Critique of uncritical AI adoption in academia drawing on neuroscience, epistemology, and publishing trends.

- **[Weber-Wulff et al. (2023) – Testing of Detection Tools for AI-Generated Text](https://doi.org/10.1007/s40979-023-00146-z)** – Evaluation of 14 AI-text detectors showing that they are neither accurate nor reliable.

- **[Wei et al. (2025) – From AI for Science to Agentic Science](https://arxiv.org/abs/2508.14111)** – Survey of autonomous scientific discovery systems (“agentic science”) across disciplines including physics and astronomy.


## Other Awesome Lists

- [Awesome Artificial Intelligence Regulation](https://github.com/ethicalml/awesome-artificial-intelligence-regulation) – Policies, regulations, and ethical frameworks for AI governance.
- [Awesome Responsible AI](https://github.com/AthenaCore/AwesomeResponsibleAI) – Resources on trustworthy and human-centered AI.
- [Awesome AI Scientists](https://github.com/natnew/Awesome-AI-Scientists) – Resources on AI systems that assist scientific discovery.
- [Awesome AI Ethics](https://github.com/awesomelistsio/awesome-ai-ethics) – Frameworks, research, and tools for responsible AI development.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0][CC0-badge]][CC0-link]


See [LICENSE](LICENSE).

[awesome-badge]: https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg
[awesome-link]: https://github.com/sindresorhus/awesome
[CC0-badge]: http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg
[CC0-link]: https://creativecommons.org/publicdomain/zero/1.0/
