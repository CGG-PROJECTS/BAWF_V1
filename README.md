
**About this Database**

The BAWF Project is about developing an AI-informed resource designed to support vocabulary, morphology, and word-family instruction.
Morphology is the study of how words are built from meaningful units, including bases, roots, prefixes, and suffixes.
AI can make mistakes!! There will be updates and version improvements over so time—stay tuned :).
Use it to explore English word families, compound words, basewords, roots, prefixes, suffixes, and frequency measures.
Use the curated tab to focus on familiar (widely known) word families for teaching.
Use the full database tabs to explore the broader lexicon, drawn from Wiktionary and large English corpora.
Use sorting, filtering, AI prompts, dictionary links, and etymology links.
Use the 'Action' buttons to check morphology, get more word information, alternative parses etc.
Download the raw compressed CSV files for offline use and advanced analysis.
This is an open project for the community, Creative Commons—you can use it, change it, and do what you want with it!
**See a dry academic article on the project here :)** Green C, Hiebert EH and Coxhead A (2026) Patterns of morphology in children’s print: estimates of polymorphemic vocabulary using an innovative, AI-informed database of British and American word families. Front. Psychol. 17:1985734. DOI: 10.3389/fpsyg.2026.1985734

**Be inspired by joyful word learning and reading — dive in and explore!**

**This work is licensed under a Creative Commons Attribution 4.0 International License**

Note: Large datasets may need 30–60 seconds to load.
Not sure which database tab to use? Start here. Ask in plain English, build teaching word sets, generate classroom prompts, and send words to activities or word clouds.
✨ Start with AI Morphology Studio
✨Full Database: Word Families: Main database
✨Full Database: Compound Words
✨Advanced Query Builder
✨Word Cloud Generator
✨Curated Word Family List: Frequent and Familiar Words: This curated word family list contains frequent and familiar word families that most people know and that cover much of the text children read.
The full database is for exploring all words attested in the largest current corpora. The focused database is a trimmed version that lists only word families with familiarity ratings above approximately 3.5.

**Core Word Information**
Word: The surface wordform.
Word_frq_Zipf / Word_frq_Zipf_Recomputed: Zipf frequency score of the wordform. This is a log10 frequency scale based on frequency per billion words. In this app, estimated frequency per million words is computed as 10^(Zipf - 3). A Zipf score of 3 is about 1 per million, 4 is about 10 per million, 5 is about 100 per million, 6 is about 1,000 per million, and 7 is about 10,000 per million.
FLemma: Lemma or dictionary-style headword when available.
GPT_Coded_Word_Parts: GPT-assisted morphological breakdown of the word.
Baseword Information
Baseword: The central baseword of a word family (LLM suggested).
Baseword_frq_Zipf: Word-family frequency computed from family members.
Baseword_Family_Size: Number of known wordforms in the baseword family.
ALTBASE Nation_2017:Alternative baseword options from the BNC-COCA word family list (level 6) developed by Paul Nation.
ALTBASE Brysbaert et al 2016: Alternative baseword options from a word family list developed by Marc Brysbaert and colleagues .
ALTBASE Batsuren et al _2021: Alternative baseword options from Morphynet - a derivation-base pairing wordlist extracted form Wiktionary by Batsuren and colleagues.
Roots, Prefixes, and Suffixes
GPT_Root: Main root identified by GPT-assisted morphological analysis.
Greek_Latin_Root_1: First identified classical root when available.
Prefix_1 to Prefix_3: LLM-estimated Prefixes identified in the word.
Suffix_1 to Suffix_6: LLM-edtimated Suffixes identified in the word.
Greek_Latin Wiktionary Meaning and Etymology:: I extracted from Wiktionary the Greek or Latin etymological words and meanings (when available) by using some code and having an LLM read the dictionary entry. .
Educational Measures
N_Morphemes_from_GPT_parse_without_inflections: Morpheme count estimate excluding inflectional morphemes.
N_Morphemes_from_GPT_parse_plus_inflections: Morpheme count estimate including inflectional morphemes.
Reading AoA Green et al._ 2025: Estimated reading age of acquisition.
Vocabulary eXpected Grade Level Flor et al._ 2024: Estimated vocabulary grade level.
GPT_Familiarity Brysbaert et al._ 2024: GPT-estimated familiarity rating when available (>3.5 are commonly known).





**Selected References**
Green, C., Hiebert, E. H., & Coxhead, A. (2026). Patterns of morphology in children’s print: Estimates of polymorphemic vocabulary using an innovative, AI-informed database of British and American word families. Frontiers in Psychology, 17, Article 1985734
Batsuren, K., Bella, G., & Giunchiglia, F. (2021). MorphyNet: A large multilingual database of derivational and inflectional morphology. In N. Gala & A. Nicolai (Eds.), Proceedings of the 18th SIGMORPHON Workshop on Computational Research in Phonetics, Phonology, and Morphology (pp. 39–48). Association for Computational Linguistics.
Brysbaert, M., Martínez, G., & Reviriego, P. (2025). Moving beyond word frequency based on tally counting: AI-generated familiarity estimates of words and phrases are an interesting additional index of language knowledge. Behavior Research Methods, 57, Article 28. https://doi.org/10.3758/s13428-024-02561-7
Brysbaert, M., Stevens, M., Mandera, P., & Keuleers, E. (2016). How many words do we know? Practical estimates of vocabulary size dependent on word definition, the degree of language input and the participant’s age. Frontiers in Psychology, 7, Article 1116. https://doi.org/10.3389/fpsyg.2016.01116
Davies, M. (2019). The Corpus of Contemporary American English (COCA): One billion words, 1990–2019.
Flor, M., Holtzman, S., Deane, P., & Bejar, I. (2024). Mapping of American English vocabulary by grade levels. ITL – International Journal of Applied Linguistics, 175(1), 25–45. https://doi.org/10.1075/itl.22025.flo
Love, R., Dembry, C., Hardie, A., Brezina, V., & McEnery, T. (2017). The Spoken BNC2014: Designing and building a spoken corpus of everyday conversations. International Journal of Corpus Linguistics, 22(3), 319–344. 
Nation, I. S. P. (2017). The BNC/COCA Level 6 word family lists (Version 1.0.0) [Data set]. Victoria University of Wellington. http://www.victoria.ac.nz/lals/staff/paul-nation.aspx
