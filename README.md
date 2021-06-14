# Gender-pronoun-resolution
Pronoun resolution is part of coreference resolution, the task of pairing an expression to its referring entity. This is an important task for natural language understanding, and the resolution of ambiguous pronouns is a longstanding challenge.
Unfortunately, recent studies have suggested gender bias among state-of-the-art coreference resolvers. Google AI Language aims to improve gender-fairness in modeling by releasing the Gendered Ambiguous Pronouns (GAP) dataset, containing gender-balanced pronouns (50% of its examples containing feminine pronouns, and 50% containing masculine pronouns).
# Technologies

▪️ [Pandas](https://pandas.pydata.org/)

▪️ [Numpy](https://numpy.org/)

▪️ [PyTorch](https://pytorch.org/)

▪️ [BERT model](https://pypi.org/project/pytorch-pretrained-bert/)

▪️ [Helper bot](https://github.com/ceshine/pytorch-helper-bot)

# Dataset
Dataset was taken from [GAP Dataset Github Repo](https://github.com/google-research-datasets/gap-coreference). It contains 2000 rows and 9 columns:

▪️ ID -  Unique identifier for an example (Matches to Id in output file format)

▪️ Text - Text containing the ambiguous pronoun and two candidate names (about a paragraph in length)

▪️ Pronoun - The target pronoun (text)

▪️ Pronoun-offset - The character offset of Pronoun in Text

▪️ A - The first name candidate (text)

▪️ A-offset - The character offset of name A in Text

▪️ B-offset - The character offset of name B in Text

▪️ URL - The URL of the source Wikipedia page for the example
