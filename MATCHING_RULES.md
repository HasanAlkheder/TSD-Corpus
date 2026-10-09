# Matching rules (used for all reported GAS / GER / GCR values)

Detected label per target sentence: Female, Male, or None (no marker).

## Syrian Arabic (SYR) -- 44 forms (25 F, 19 M)
1. Split the sentence on whitespace.
2. Strip surrounding punctuation from each token (ASCII punctuation plus ؟ ، ؛).
3. Compare each token to the lexicon by exact string match (diacritics retained).
4. The first matching token determines the gender. No match -> None.
No clitic-stripping or morphological normalization.

## Modern Standard Arabic (MSA) -- 16 forms (8 F, 8 M)
1. Check whether each lexicon form occurs in the sentence (substring match, diacritics retained).
2. Only feminine forms found -> Female; only masculine forms found -> Male.
3. Forms of both genders found, or none -> None.

## Metrics
None cases enter neither the GAS nor the GER numerator; both stay normalized by the full evaluation size N, so undetected = 1 - (GAS + GER).
