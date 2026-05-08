# KWIC Searcher
A desktop tool for **Key Word In Context (KWIC)** search <br>Find any term inside a webpage or local file to show the word in context with additional linguistic information. Supports session history, text analysis, and saving/loading results as XML.
## Authors
- [@KylejustKyle](https://github.com/KylejustKyle)
- [@danielclas](https://github.com/danielclas)
- [@Wufanghsien](https://github.com/Wufanghsien)
## Features
- Search web URLs or local files for a keyword/needle
- Configurable left and right offset neighbors returned with each hit
- Case-insensitive search option (`A=a` mode)
- Session history viewer for all searches in the current run
- Detailed text analysis view of the current search
- Export all session results to XML
- Import and merge previous XML sessions (no duplicates)
## How to use
| Step | Action |
|------|--------|
| 1 | Enter a URL or local file path in the input field |
| 2 | Or click the file chooser button to browse for a local file |
| 3 | Type the search term (keyword/needle) you want to find |
| 4 | Set search options: enable `A=a` for case-insensitive matching |
| 5 | Choose how many neighboring words to return left and right of each hit |
| 6 | Click **Search** to run |
| 7 | Results populate in the results area below |
| 8 | Click **History** to review all searches this session |
| 9 | Click **Save XML** to export all session searches |
| 10 | Click **Load XML** to import a previous session, new entries are appended, duplicates are skipped |
## Running the app
- A pre-built executable JAR (with all dependencies bundled) is provided in the repository.<br>
- Download the .jar file

```bash
java -jar KWIC-searcher.jar
```
- run this in the terminal
