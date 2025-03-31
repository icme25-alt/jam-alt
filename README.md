# Directory structure
Long-form Jam-ALT transcripts with inline nonlexical annotations are in `lyrics_tagged/{name}.txt`.
Line timings for each song are in `line_timings/{name}.csv`. Every non-empty line in the long-form transcripts has a corresponding entry in the line timings csv file.

## Non-lexical annotations
```
<nl> (Uh, ah-ja, eh-jo) </nl>
Ich mach' Musik, Musik
```
Non-lexical annotations are provided as inline tags `<nl>` and `</nl>` 
in the long-form transcripts and short-form merged line timings, as shown above.
Any words between the opening and closing tags are non-lexical vocables.
