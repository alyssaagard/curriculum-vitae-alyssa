# Curriculum Vitae

The source and published version of the curriculum vitae of Alyssa I. Agard, historian and defense policy researcher.

The document is a single self-contained HTML file. It carries its own styles, print rules, and structured data, and it loads no external stylesheets, fonts, scripts, or trackers. It is served through GitHub Pages at a custom subdomain.

**Published at:** https://documents.alyssaagard.dev/#curriculum-vitae

## Contents

| File | Purpose |
| --- | --- |
| `index.html` | The curriculum vitae. Markup, styles, print rules, and JSON-LD structured data in one file. |
| `CNAME` | Custom domain record used by GitHub Pages. |
| `favicon.ico`, `favicon-32.png`, `favicon-192.png`, `apple-touch-icon.png` | Icon set, referenced by relative path so the page renders correctly whether it is served from the custom domain or from a project subpath. |
| `LICENSE` | Copyright terms. See Licensing below. |
| `README.md` | This file. |

## Design conventions

The page follows the same conventions as the Word and PDF versions of the curriculum vitae, so that a reader who prints the web page and a reader who receives the file see the same document.

- Times New Roman throughout, with normal letter spacing.
- Black text only. Links are black in both the default and visited states, so the printed page carries no color.
- Dates are set flush right against the institution or role they belong to.
- The header lists location, telephone, LinkedIn, email, and website, and nothing further.
- A print stylesheet suppresses interface elements and sets margins, so that printing to PDF from the browser yields a clean document.
- A dated stamp near the foot of the page records when the content was last revised.

## Structured data

The page carries a JSON-LD `Person` block so that search engines and scholarly indexes read the record correctly. Two points govern its accuracy and should be preserved in any revision:

1. The `jobTitle` value states the role at Agard Research Associates Inc. Agard Research Associates is a nonpartisan 501(c)(3) policy analysis institute, and its work consists of policy analysis, financial administration, and compliance.
2. The defense research, quantitative modeling, and simulation software are independent and unaffiliated with Agard Research Associates. They are described in their own section of the document and must not be attributed to the organization in either the visible text or the structured data.

ORCID: https://orcid.org/0009-0008-5783-2437

## Updating the document

1. Edit `index.html` directly. Entries follow the existing markup patterns, so a new publication or position can be added by copying the nearest comparable block and replacing its content.
2. Update the last-revised stamp.
3. If the entry also appears in the Word and PDF versions of the curriculum vitae, revise those in the same sitting. The web page and the distributed files are expected to agree.
4. Commit to the default branch. GitHub Pages rebuilds and republishes the site automatically.
5. Open the published page once after deployment and confirm that the page loads under the custom domain, that the icons resolve, and that every outbound link still answers. Repository links are the most common point of failure, because moving a repository between accounts changes the address of its Pages site.

## Citation

Agard, Alyssa I. *Curriculum Vitae*. https://documents.alyssaagard.dev/#curriculum-vitae

## Licensing

The contents of this repository, including the text of the curriculum vitae and its markup, are the copyrighted work of Alyssa I. Agard. All rights are reserved except as stated in `LICENSE`. The document may be read, printed, and cited. It may not be republished, redistributed, or adapted, in whole or in part, without written permission.

## Contact

aa@alyssaagard.dev
