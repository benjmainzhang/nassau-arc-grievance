# Nassau ARC Grievance Helper (a Claude skill)

A free skill that helps Nassau County, NY homeowners prepare their own property tax grievance with the Assessment Review Commission (ARC). Claude works out what your assessment implies your home is worth, screens the recent sales AROW gives you, picks the honest comparables, and drafts the Part D note and a requested value. You file it yourself in AROW.

> **Unofficial.** This project is not affiliated with, endorsed by, or connected to Nassau County, the Assessment Review Commission, or the Department of Assessment. It is general help, not legal or tax advice. You are responsible for everything you submit, and you certify it is accurate when you file.

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

## When to use it

The filing window opens in early January when the tentative roll is published and usually closes around March 1. Check the ARC website for this year's dates. Filing is free, and ARC cannot raise your assessment because you filed.

## Keep your details private

Your county pages, ARC letters and Claude's results contain your name, address, parcel ID and contact details. Don't post them in public issues, forums or social media. If you report a problem with the skill, describe it with made-up numbers.

## Contributing

Dates and ARC's level of assessment change every year. If something is out of date or a rule is wrong, open an issue or pull request. Please keep real people's names, addresses and parcel IDs out of anything you submit.

## License

MIT - see [LICENSE](LICENSE).
