# Persian (Iran)

This page records provenance and page references for a historical Iranian
institutional source. It does not reproduce the source or its Braille tables.

## 2014 institutional manual

- _title_: مجموعه علائم بریل
- _descriptive English title_: Collection of Braille Signs
- _issued by_: Iran's National Organization for Special Education
  (سازمان آموزش و پرورش استثنایی کشور)
- _responsible unit_: Deputy for Educational Planning and Rehabilitation
  (معاونت برنامه‌ریزی آموزشی و توان‌بخشی)
- _published_: Iran, 1393 SH / 2014 CE
- _language_: Persian, with sections covering other languages and notations
- _extent_: 371 PDF pages: an unnumbered cover followed by printed pages 1–370
- _status_: official-institutional historical source; current normative status
  unverified

### Provenance

The title appears in an [archived 2014 catalog of Iran's Ministry of
Education](https://web.archive.org/web/20140828055145/http://www.medu.ir/portal/Home/ShowPage.aspx?Object=DirectoryView%26CategoryID=5e202802-bad0-431b-b0d7-5b9dc4967a3b%26LayoutID=ea1a5bb4-1ae7-4077-8d7c-da52e62d0808%26DirectoryID=b55838a1-24b3-4ab0-af00-b2a5fb2fbb00%26ID=474d0152-09bf-4108-9197-f80752900987)
under material for visually impaired students. The catalog object UUID is
`70a072ca-f083-45ad-a1ff-95614de30bc5`.

Two contemporaneous pages provide additional provenance:

- a [14 Tir 1393 announcement](https://7mhr.blogfa.com/post/101) pointing
  readers to the Ministry catalog; and
- an [educator's reference page](https://blindsteacher.blogfa.com/post/34)
  linking both the Ministry listing and a public mirror.

A [surviving mirror landing
page](https://s4.picofile.com/file/8171401192/alaem_brill.rar.html) provides the
archive from which the fingerprints below were calculated. The former official
download binary was not recovered, so the mirror has not been proven
byte-identical to it.

### Artifact fingerprints

These fingerprints identify the recovered mirror artifacts. Neither artifact
is stored in this repository.

| Artifact | Size | SHA-256 |
| --- | ---: | --- |
| `alaem_brill.rar` | 4,174,566 bytes | `12a2179180ba0375e77a517a86fffd2f5c1326f9917608a76a8c40cd5db222cb` |
| `alaem brill.pdf` | 9,697,432 bytes | `7974b08c12ece7242b2a435e71c5c8cacc2f296bad8728544a310cb33c9ada63` |

The PDF member has RAR CRC-32 `526DF072`.

### Page map

The cover is PDF page 1 and has no printed page number. For the remainder of
this file, the PDF page number is the printed page number plus one.

| Subject | Printed pages | PDF pages |
| --- | ---: | ---: |
| Introduction and methodology | 12–18 | 13–19 |
| General material and history | 19–30 | 20–31 |
| Persian literary Braille | 31–95 | 32–96 |
| Persian alphabet | 32–33 | 33–34 |
| Persian punctuation and arithmetic signs | 34–40 | 35–41 |
| Persian document and transcription conventions | 41–48 | 42–49 |
| Persian orthography | 49–67 | 50–68 |
| Persian short forms | 68–89 | 69–90 |
| Persian phonetics | 90–95 | 91–96 |
| Arabic and Quranic material | 96–100 | 97–101 |
| English | 101–135 | 102–136 |
| English Grade 1 | 102–103 | 103–104 |
| English Grade 2 | 104–120 | 105–121 |
| English phonetics and umlauts | 121–135 | 122–136 |
| Mathematics and sciences | 136–206 | 137–207 |
| Computer Braille section divider | 207 | 208 |
| Computer Braille introduction | 208–209 | 209–210 |
| American Computer Braille | 210–213 | 211–214 |
| British Computer Braille | 214–217 | 215–218 |
| Music | 218–290 | 219–291 |
| Iranian music | 277–284 | 278–285 |
| Appendices | 291–363 | 292–364 |
| Sources | 364–370 | 365–371 |

The computer section describes American and British ASCII-era Computer
Braille. It is not an explicit Persian eight-dot Unicode code. The manual also
predates an explicit model for Unicode normalization, ZWNJ, bidirectional text,
cursor routing, and translation round trips. These behaviors require separate,
modern specification and validation.

The PDF uses embedded Braille fonts without usable Unicode mappings, and its
Persian text extraction is affected by bidirectional ordering. Any future
machine-readable transcription should therefore be independently transcribed
twice and checked against rendered pages.

## Nonclaims and reuse status

- This page does not claim that the 2014 manual is Iran's current standard or
  that no later edition exists.
- “Persian Braille 2026” is a project label, not a national standard or an
  endorsement by the issuing organization.
- No 2026 approval by an Iranian authority or validation by native blind
  Persian Braille readers is claimed.
- The mirror's relationship to the former official binary is supported by
  historical links but not by matching cryptographic fingerprints.
- No redistribution license was found. The PDF, RAR, page images, embedded
  fonts, OCR text, and manual content are intentionally not included here.
- The links, hashes, metadata, and page map document provenance; they do not
  grant permission to reproduce the source.
- This page is not a transcription of the manual and does not define a Persian
  literary or computer-Braille translation table.

The corresponding implementation audit and open policy questions are tracked
in [liblouis/liblouis#2053](https://github.com/liblouis/liblouis/issues/2053).
