# Hebrew fiction in English translation, US editions, 1948–2026

A bibliography of **419 Hebrew-language works of adult fiction published in English translation in US editions**, 1948–2026.

## The data

`hebrew-fiction-english-translation-US-editions-1948-2026.csv` — 419 rows, one per book, UTF-8, CRLF line endings.

| Column | Notes |
|---|---|
| `Year` | Year of the US edition, 1948–2026. No rows for 1949, 1950, 1953, 1954, 1959, 1964, 1965. |
| `Author` | Author as credited; 184 distinct authors. Translators are not recorded. |
| `Title` | English title of the US edition; 418 distinct strings. |
| `US Publisher` | **Blank in 209 rows** — see the caveat below. 85 distinct publishers. |
| `Source dataset` | Which compilation the row came from (see below). |

Books per decade:

| Decade | Books | | Decade | Books |
|---|---|---|---|---|
| 1940s | 3 | | 1990s | 60 |
| 1950s | 7 | | 2000s | 83 |
| 1960s | 21 | | 2010s | 111 |
| 1970s | 37 | | 2020s (to 2026) | 48 |
| 1980s | 49 | | | |

Most-represented authors: Aharon Appelfeld (21), Amos Oz (19), Yoram Kaniuk (12), A. B. Yehoshua (10), David Grossman (10), Etgar Keret (10), S. Y. Agnon (10).

Most-represented publishers, among rows that record one: Toby Press (18), Schocken Books (11), Dalkey Archive (9), Houghton Mifflin Harcourt (9), HarperCollins (8), New Vessel Press (9).

## Sources

The `Source dataset` column records where each row came from:

| Label | Rows | |
|---|---|---|
| `Amit` | 209 | Yuval Amit's dissertation bibliography of Hebrew books published in English translation, 1948–2004 |
| `USsurvey` | 199 | A survey of US editions covering 2004–2026 |
| `Amit+USsurvey` | 6 | In both |
| `Omri Asscher` | 5 | From the work of Omri Asscher on Hebrew literature in American translation |

The split is chronological: the Amit bibliography supplies almost everything before 2004, and the US survey almost everything from 2004 on.

## Caveats

- **`US Publisher` is missing for half the rows.** 205 of the 209 blanks are pre-2004 rows from the Amit bibliography, which did not record the US publisher in a form carried over here. A blank means *not recorded*, not "no publisher". Publisher-level counts are therefore only usable for 2004 onward.
- **The pre- and post-2004 halves were compiled by different methods**, so a change in counts around 2004 may reflect the change in source rather than a change in publishing.
- **2026 is a part-year** (3 rows: Yishay Ishi Ron, *The Girl Who Rode the White Lion*; Zeruya Shalev, *Fate*; Noa Yedlin, *House Arrest*), so it is not comparable with full years. Shalev's *Fate* was previously dated 2024 here; the year was corrected to 2026 to match the publisher's own listing (Other Press, 13 October 2026).
- **Scope is adult fiction in US editions.** UK-only and other non-US editions are out of scope, as are children's and young-adult titles.
- **Inclusion depends on each source's own criteria**, which are not reproduced here. Treat yearly counts as a lower bound on Hebrew fiction translated into English.

## Licence

The underlying bibliographic facts are not copyrightable. Please cite the original compilations (Amit; Asscher) when the rows derive from them.
