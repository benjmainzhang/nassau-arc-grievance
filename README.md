# Nassau ARC Grievance Helper (a Claude skill)

A free skill that helps Nassau County, NY homeowners prepare their own property tax grievance with the Assessment Review Commission (ARC). Claude works out what your assessment implies your home is worth, screens the recent sales AROW gives you, picks the honest comparables, and drafts the Part D note and a requested value. You file it yourself in AROW.

> **Use at your own risk.** This is an unofficial, unsupported hobby project. It is not legal, tax, financial or appraisal advice, it comes with no warranty of any kind, and it may be wrong or out of date. You are solely responsible for what you file. Read the full [disclaimer](#disclaimer--use-at-your-own-risk) before using it.

## Disclaimer – use at your own risk

By installing or using this skill, you agree to the following:

- **Not professional advice.** Nothing produced by this skill or by Claude while using it is legal, tax, financial, real estate or appraisal advice. No attorney-client, advisor-client or other professional relationship is created. For advice about your situation, consult a licensed attorney, tax professional or appraiser.
- **AI makes mistakes.** Claude can misread documents, miscalculate, pick unsuitable comparable sales, or state rules, rates and dates incorrectly. Check every figure, comparable sale, date and statement against the original county records before you rely on it.
- **No guarantee of results.** Using this skill does not guarantee a reduction in your assessment or taxes, or any particular outcome. Past results described anywhere in this project are illustrative only.
- **Rules change.** Filing deadlines, ARC's level of assessment, the sales window and county procedures change every year and may change without notice. Confirm everything with the [Assessment Review Commission](https://www.nassaucountyny.gov/arc) before filing. Missing a deadline because you relied on this project is your responsibility.
- **You are responsible for your filing.** You decide what to submit, and you certify its accuracy when you file. Never submit information you have not verified or that you know to be inaccurate.
- **Unofficial and unaffiliated.** This project is not affiliated with, endorsed by or connected to Nassau County, the Assessment Review Commission, the Department of Assessment, or Anthropic. "Claude" is a product of Anthropic; this skill is an independent, community-made add-on.
- **Your data.** Documents and details you share with Claude are handled under Anthropic's terms and privacy policy, not by this project. Decide for yourself what you are comfortable sharing.
- **No warranty, no liability.** This project is provided "as is", without warranty of any kind, express or implied. To the fullest extent permitted by law, the authors and contributors are not liable for any loss, damage, missed deadline, tax liability, penalty or other consequence arising from its use. See the [LICENSE](LICENSE) for full terms.
- **No support.** There is no obligation to answer questions, fix problems or keep this project up to date.

If you do not agree with these terms, do not use this skill.

## Who it's for

- Nassau County homeowners with a **Class 1** property (1-3 family house or residential condo)
- Filing **for yourself** at ARC (representative type "Self" in AROW)

It does not cover Suffolk County, New York City, commercial property, or Small Claims (SCAR) hearings.

## Install it in the Claude app

1. Download `nassau-arc-grievance.zip` from the [Releases](../../releases) page. Don't unzip it.
2. In Claude, open **Customize > Skills**, choose to create a skill, then **Upload a skill** and pick the ZIP.
3. Make sure the skill is switched on, and that code execution / file creation is enabled in your settings.

Menu names change from time to time; if these don't match what you see, check Anthropic's help article on using skills in Claude. Uploaded skills are private to your account.

**Claude Code users** can copy the `nassau-arc-grievance` folder into `~/.claude/skills/`.

## Get your pages to Claude

Claude needs three things from you. The simplest way, in any browser, is to print each page to PDF (Ctrl+P or Cmd+P, then "Save as PDF") and attach the files to your chat.

1. **Your property's Values tab** on the Nassau County Land Records Viewer (your tentative assessed value, size, year built).
2. **The AROW "Find Sales" list** for your home - every page of it. Tip: raise "Rows displayed per page" so it all fits on one page.
3. **Last year's ARC settlement offer or determination**, if you have one.

Also tell Claude your purchase price and date, and anything that hurts your home's value (busy road, repairs needed, flood zone).

If you use Google Chrome with the Claude extension, Claude can read the pages directly instead. It only reads; it will not check boxes or submit anything.

## Example prompt

> I want to grieve my Nassau property taxes for the coming year. Attached are my property's Values page, both pages of my AROW sales list, and last year's ARC settlement. I bought the house in 2019 for $950K. Which comps should I pick, and what should I write in Part D?

Treat Claude's answer as a starting draft. Check every sale, number and date against the county's own pages before you file anything.

## When to use it

The filing window opens in early January when the tentative roll is published and usually closes around March 1. Check the ARC website for this year's dates. Filing is free, and ARC cannot raise your assessment because you filed.

## Keep your details private

Your county pages, ARC letters and Claude's results contain your name, address, parcel ID and contact details. Don't post them in public issues, forums or social media. If you report a problem with the skill, describe it with made-up numbers.

## Contributing

Dates and ARC's level of assessment change every year. If something is out of date or a rule is wrong, open an issue or pull request. Please keep real people's names, addresses and parcel IDs out of anything you submit.

## License

MIT - see [LICENSE](LICENSE).
