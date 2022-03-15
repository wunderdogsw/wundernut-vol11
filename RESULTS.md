# RESULTS

## Jury Round 1

### Qualified:

1. Works with message & verify
2. Works with message & verify
8. Works with message & verify
9. Works with message & verify
11. Works with message & verify
12. Works with message & verify

### Disqualified:

3. Works with message, missed last dot from verify
4. Could not get to run main Scala function with the instructions
5. Looks good, but does not read message nor verify
6. Python file only used as "cli", all logic in SQLite (views). Very slow. Only works with message, didn't work with verify. Only produced out long and short beeps + spaces, didn't produce text message.
7. Could not get to work with instructions
10. Works with message, missed last dot from verify

## Jury Round 2

### [Submission 1](https://github.com/jpohjolainen/wundernut-vol11):
- Jussi: Looks very clear and compact
- Ari: Short function names, could be split
- No tests
- Does not look modern Python code
- -> disqualified due not having tests

### [Submission 2](https://github.com/anttiz/wav-to-morse):
- Process diagram
- Tests
- Linter
- Jussi: audioToMorse.ts starts with clear and compact functions, but the main function "processFile" looks a bit confusing
- Ari: Enough comments to know what happens
- -> disqualified in favor of [Submission 9](https://github.com/anttiz/wav-to-morse-web) from same author (improved)

### [Submission 8](https://github.com/mkouhia/morse-audio-decoder):
- Technical planning done properly with Jupyter notebook
- Formatting
- Linting
- Coverage
- Tests
- Bit conversion done properly (was not required, though)
- Good thoughts for further development (noise, changing pitch, etc)
- Ari: A lot of code, but very clear & well-documented

### [Submission 9](https://github.com/anttiz/wav-to-morse-web):
- By same author as [submission 2](https://github.com/anttiz/wav-to-morse), same process diagram, tests & linter
- UI done with lit (web components)
- We'll disqualify [submission 2](https://github.com/anttiz/wav-to-morse) in favor of using this, since this is "improved version" of the same basically

### Submission 11:
- No tests, formatting, linting, coverage
- Using dependencies
- Ari: Code written in small & compact functions, easy to read
- Jussi: Functional code, some of the nested function calls could be written more openly (f.e. extract_words(unit_beeps(state_switches(timed_states(read_samples(path))))) ...)
- to_units "2 * base_unit" short break and "5 * base_unit" long break could be somehow explained?
- -> disqualified due not having tests

### [Submission 12](https://github.com/tfriman/wundernut-vol11):
- Couple of tests
- No formatting, linting, coverage
- Jussi: morse->text "main function" is very explaining how the program works
- Ari: Small functions, comments
- Extraneous dependency


## Jury Round 3

Focus on [code quality metrics](https://blog.cloudboost.io/code-quality-metrics-67dc861ac139) analysis.

### [Submission 8](https://github.com/mkouhia/morse-audio-decoder):
- Extensibility: Explained in the documentation
- Maintainability: Extensive tests help to make any changes
- Readability: Small functions with documentation, functions and variables are properly named
- Clarity: All tests and program files are easy to comprehend
- Efficiency: Good library used for basic operation
- Documentation: Prestudy and technical description are good

### [Submission 12](https://github.com/tfriman/wundernut-vol11):
- Maintainability: Basic tests exist
- Readability: Compact and clearly divided
- Efficiency: Good library used for basic operations

### [Submission 9](https://github.com/anttiz/wav-to-morse-web):
- Maintainability: Boundary tests exist
- Documentation: Process diagram
