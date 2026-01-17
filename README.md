# scala-cobalt-35

A small Scala tool that computes text statistics for cobalt.

## Goal
- Provide quick text metrics for cobalt documents.
- Report top word frequencies for fast inspection.

## Usage
scala Main.scala data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Notes
- Only ASCII letters and digits are treated as word characters.
