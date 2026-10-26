# Data de-identification checklist

A free, 11-page checklist for company owners and the people who clean the data: **[download the PDF](data-de-identification-checklist.pdf)**. The same file is on the website: [aitrainingdatabroker.com/de-identification/](https://aitrainingdatabroker.com/de-identification/?utm_source=github).

"De-identified" means different things under different laws, so the checklist works as a sequence you can follow and sign off step by step.

## The steps in short

1. **Decide which rules apply.** Each privacy law sets its own test for "de-identified". Decide which ones apply before you change a single file.
2. **Inventory.** Write down every system, whose information is in it, and where it hides, before anything is exported.
3. **Remove the direct identifiers.** Anything that names or reaches a person comes out, or becomes a placeholder, under every rule.
4. **Dates and places.** Health-data rules keep only the year and a coarse part of a ZIP code. Anything finer needs a qualified expert. Check the exact wording of the rule that applies to you.
5. **Read the free text.** Most personal details in company data sit in places no field labels (signatures, quoted replies, file names), so people read the text after software has run.
6. **Check the combinations.** Fields that are harmless alone can single someone out together. Count how many records share each combination.
7. **Test what is left.** Run the automatic checks, then have someone who did not clean the data try to identify people in it.
8. **Keep the record.** Keep a written record of every step, put the limits in the contract, and check again when anything changes.

The PDF adds worksheets (a data map and an identifier log), worked examples and a check for each step.

## What it is not

It is not legal advice, and a qualified expert signs any HIPAA Expert Determination, not us. We do de-identification work ourselves as a service: [how it works and what it costs](https://aitrainingdatabroker.com/de-identification/?utm_source=github).

## Sharing

You may share the PDF unchanged, with credit and a link to [aitrainingdatabroker.com](https://aitrainingdatabroker.com/?utm_source=github).

[Back to the profile](../README.md)
