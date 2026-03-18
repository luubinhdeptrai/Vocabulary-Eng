Use this template when adding vocabulary entries. Format must match the example in `vocab-1.md` exactly.

Template (produce entries exactly like this):

1. <word> (<IPA> | Phát âm)

> **0. Level | Trình độ**
> * <CEFR level> — short note on how common/important the word is
>
> **1. Meaning | Nghĩa**
> * (part of speech) <Vietnamese meaning> — short English gloss (optional)
> * (optional) second meaning
>
> **2. Example | Ví dụ**
> * EN sentence — VN translation
> * optional second example
>
> **3. Word family | Họ từ (table)**
> | Word | Part of Speech | Meaning (Vietnamese) |
> |---|---:|---|
> | baseword | pos | meaning |
> | derived | pos | meaning |
>
> **4. Collocations | Cụm từ thường đi với**
> * collocation — VN meaning
> * collocation — VN meaning
>
> **5. Synonyms | Từ đồng nghĩa**
> * synonym — short gloss
> * synonym — short gloss
>
> **6. Distinction | Phân biệt nhanh**
> * short comparison with 1–2 similar words (one-line)
>
> **7. Memory tips | Mẹo ghi nhớ**
> * one short mnemonic or image

---

Rules and notes (must follow):

- Number each vocabulary entry (e.g., `1.`, `2.`) on the word line only; do NOT include the word "Word:".
- Put pronunciation inline on the same line as the word: `1. word (IPA | Phát âm)`.
- Separate entries with a single `---` line.
- Put the explanatory content (Level → Memory tips) inside a Markdown blockquote (each line starts with `>`) as shown above — this highlights the explanation and avoids formatting issues.
- Keep entries concise: 1–2 meanings, 1–2 examples, 3–5 collocations/synonyms.
- Use the Word family table inside the blockquote exactly as shown (a 3-column Markdown table).
- Prioritize the most common meaning first and use practical examples.
- Output entries into `vocab-1.md` for tracking.

When you give me a word, I'll format and append it to `vocab-1.md` using this template.