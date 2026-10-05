# Redbrook Carrier Questions

Questions from carriers and Redbrook's proposed and final responses, with the original correspondence and response PDFs kept alongside the editable text.

## Carrier Register

| Carrier | Questions received | Questions | Response status | Record |
| --- | --- | --- | --- | --- |
| Concert | 2026-10-01 | 7 | Final | [Questions and responses](carriers/concert/2026-10-01/questions-and-answers.md) |

## File Organization

Each set of questions has its own folder:

```text
carriers/<carrier>/<YYYY-MM-DD>/
  questions-and-answers.md
  source.pdf
  responses.pdf
```

Use the date the questions were received. Keep follow-up question sets in a new dated folder. If more than one set arrives on the same day, append a short topic to the folder name.

- `questions-and-answers.md` is the editable record used to track changes in Git.
- `source.pdf` preserves the original correspondence. Other source formats may be kept with their original extensions.
- `responses.pdf` is the latest formatted response document, when available.

## Adding or Updating Answers

1. Create the carrier and dated folder, then copy [the template](templates/questions-and-answers.md) into it.
2. Preserve the carrier's question wording and numbering. Put each proposed answer directly below its question.
3. Use `Unanswered`, `Proposed`, or `Final` for the response status. When answers have different statuses, use `Mixed` for the set and record each response's status individually.
4. Mark answers `Final` when approved. Final does not mean sent; record a sent date only when known.
5. Add the set to the register above. Edit answers in place and commit substantive revisions so Git retains the history.
6. Refresh the response PDF after approved wording changes. Keep its presentation plain: questions in black, responses in red, with no draft labels on final responses.

The Concert set contains all seven questions and final answers from the current discussion. Its original email PDF is retained as received; the source email's draft label does not determine the approved response status.
