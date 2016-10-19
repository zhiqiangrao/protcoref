BioNLP 2011 protein coreference resolution task

Environment: Linux
Requirement: Ruby

Requirement: GENIA Sentence Splitter (./tools/geniass, existing)
             Enju parser (./tools/enju, missing, to be merged)

Requirement: ./lib/stanford-corenlp-3.6.0.jar
             ./lib/stanford-corenlp-3.6.0-models.jar

Usage:
Input path (put .txt and .a1 files): "./data/input"
Output path (generated .a2 files): "./data/output"

Run:
java -jar protcoref.jar
