+++
title = "Writing"
page_template = "page.html"
+++
## Advice on writing

### Contents
- Your paper should be easily comprehensible by its reviewers. They are far less familiar with your work than you. They may not be an expert on the topic and may not be able to afford much time on your paper.
- The introduction should convey curiosity or excitement (new problem, new solution, improved solution, impressive results, or high impact), the design novelty, substantiality, and correctness, and the evaluation relevancy and comprehensiveness.
- Conciseness: Remove every word that contributes no meaning, such as `kind of`.
- Use proper tenses: [1](https://www.unlv.edu/sites/default/files/page_files/27/GradCollege-VerbTenseScientificManuscripts.pdf) [2](https://berks.psu.edu/sites/berks/files/campus/VerbTense_Handout.pdf) [3](https://www.nature.com/scitable/topicpage/effective-writing-13815989/)

### Grammar
- Section titles should have consistent [capitalization](https://www.grammarly.com/blog/title-case-sentence-case/). I prefer sentence case.
- Avoid passive voice unless strongly justifiable. Passive voice is ambiguous because it has no subject unless followed by "by...".
    - Bad: LLM was applied to fuzzing. (Who applied it? The authors or someone else?)
    - Good: We applied LLM to fuzzing.
- Avoid [nominalization](https://en.wikipedia.org/wiki/Nominalization).
    - Bad: He made a proposal to use Rust.
    - Good: He proposed to use Rust.
- Avoid "There is/are".
    - Bad: There are many developers of Rust.
    - Good: Many developers use Rust.
    - Good: Rust has many developers.
- "Which" vs "that": Use "which" in a nonrestrictive clause and "that" in a restrictive clause. [More ...](https://www.grammarly.com/blog/which-vs-that/)
    - Wrong: Rust that is safe is popular. (This is wrong because there is only one Rust.)
    - Right: Rust, which is safe, is popular.
- Distinguish [coordinating conjunction vs conjunctive adverbs](https://www.iup.edu/writingcenter/writing-resources/grammar/common-problems-with-however-therefore-and-similar-words.html).
    - Wrong: C is dangerous, Rust is safe. (Cannot join two sentences by a comma)
    - Right: C is dangerous, but Rust is safe.
    - Wrong: C is dangerous, however Rust is safe.
    - Right: C is dangerous; however, Rust is safe.
- "Fewer" modifies countable nouns whereas "less" uncountable nouns.
    - Wrong: ten items or less
    - Right: ten items or fewer
    - Wrong: fewer feedback
    - Right: less feedback
- Use articles (`a`, `an`, `the`) properly.
    - A singular countable noun must be preceded by an article.
        - Wrong: I wrote Rust program.
        - Right: I wrote a Rust program.
        - Right: I wrote Rust programs.
    - `The` must have a reference that is unique either by fact or in the context.
        - Right: the first Rust programmer (unique by fact)
        - Right: Our team has a Rust and a C++ programmer. The Rust programmer produces the fastest, most robust code. (unique in the context)
        - Wrong: Our team has two Rust and two C++ programmers. The Rust programer is more productive than the C++ programer.
- Distinguish between [compare with and compare to](https://www.noslangues-ourlanguages.gc.ca/en/writing-tips-plus/compare-to-compare-with)
    - Right: Rust is safer compared with C.
    - Right: Some people compare Rust to a panacea for memory safety problems.
