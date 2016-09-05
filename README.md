# NLP-AuthorshipAttribution
*Predicting authors of Turkish novels using stylometric methods. I am working with Oktay Güngör on this project.*

**Project Definition**

In this project, we have been working on a corpus consisting of works from Turkish literature.
Specifically we are trying to predict the author of a given novel from some properties of the text,
which is known as the authorship attribution problem.
Our corpus has the following properties: All text are in Turkish written by a native author. All are in
their original form, meaning they were not summarized, edited, translated. We included only the
main body of work. Preface, references, author names, book names, page numbers, publisher
information were erased.

**Motivation**

An instance of an author attribution problem has attracted great attention in 2015 when researchers
attempted to identify the author of a play called “Double Falsehood”. 54 plays were analyzed: 33 by
Shakespeare, 9 by Fletcher (a colleague of Shakespeare) and 12 by Theobold (who claimed
ownership, basing the play on Shakespeare’s earlier works). The researchers hypothesized that the
way writers use language, such as the words they choose and even the length of their sentences
showed their cognitive style and temperament; and that a deep analysis of a writer's verbal output
can paint a very rich picture of that person. For example, in consideration for Shakespeare, the
frequent use of prepositions would be attributed to his rigorous education in grammar.
The researchers examined the use of function words like pronouns, articles, prepositions, and words
belonging to various content categories like emotions, family, sensory perception, and religion.
They also tried to determine how categorical the writing was, checking if the writing was heavy on
nouns, articles, and prepositions. This indicates an analytic or formal way of thinking. People who
rate high on categorical thinking tend to be emotionally distant, applying problem-solving
approaches to everyday situations. People who rate low on categorical thinking, on the other hand,
tend to live in the moment and are more focused on social matters.
By aggregating dozens of psychological features, the psychological signature of each candidate was
matched with the psychological signature of Double Falsehood to determine who the author was
most likely to be. Every measure but one identified Shakespeare as the likely author of “Double
Falsehood”. Theobald, was identified as the best match only regarding the use of content words.

**Key Concepts**

As examplified above, authorship attribution work tries to come up with measures which matches
accurately the "style" of a given text to the known style of an author, where style is defined as a set
of measurable patterns which may be unique to the author. This attribution work is based on the
linguistic area known as stylometry, which is defined as the statistical analysis of literary style. The
assumption is that authors have specific, individual, persistent and uncontrollable habits of thought
and phrasing. We may categorize writing style characteristics of a text into four:

**1. Lexical features** can be broken into two sub-categories:

**1.a) Word-based lexical features** include total number of words, words per sentence,
word-length distribution, vocabulary richness

**1.b) Character-based lexical features** include total number of characters, characters per sentence,
characters per word, and the usage frequency of individual letters.

**2. Syntactic features** refer to the patterns used for the formation of sentences. These features are
considered beyond an author’s conscious control, for instance short all-purpose words or
punctuation. For example, the difference between using the word “thus” or “hence” can constitute a
significant stylistic difference.

**3. Semantic features** can be obtained by employing NLP technology which can identify synonyms,
hypernyms, antonyms; or part-of-speech tags like nouns, verbs, adjectives.

**4. Structural features** deal with the organization and layout of the text. This set of features focus
on word structure such as the number of paragraphs and average paragraph length.

**5. Content-specific features** are words that are important within a specific topic domain. An
example of content-specific words for a topic on soccer might be “goalkeeper” or “referee”.
Carefully selected content-based information may reveal some authorial choices.
