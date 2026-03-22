# writeups

CTF challenge writeups by [aniolowie](https://ctftime.org/user/255671).

## Structure

```
writeups/
├── manifest.json               ← machine-readable index (used by portfolio site)
└── {event-slug}/
    ├── README.md               ← event overview, team, results
    └── {challenge-slug}/
        ├── README.md           ← the writeup
        ├── solve.py            ← exploit / solve script (if applicable)
        └── files/              ← challenge attachments, binaries, etc.
```

## Adding a writeup

1. Create the folder: `{event-slug}/{challenge-slug}/`
2. Write `README.md` — keep it clear, show your thought process, include the flag at the end
3. Add your solve script if there is one
4. Update `manifest.json` — add an entry to the relevant event's `writeups` array:

```json
{
  "challenge": "Challenge Name",
  "slug": "challenge-slug",
  "category": "pwn",
  "points": 500,
  "difficulty": "medium"
}
```

Categories: `pwn` · `web` · `reverse` · `crypto` · `forensics` · `misc`

## Events

| Event | Date | Location |
|---|---|---|
| [Insomni'hack 2025](./insomniahack-2025/) | 2025-03 | Lausanne 🇨🇭 |
# writeups
