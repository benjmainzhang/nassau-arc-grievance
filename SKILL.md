---
name: nassau-arc-grievance
description: Helps a Nassau County, NY homeowner prepare their own residential property tax grievance (Form AR1) with the Assessment Review Commission (ARC) - working out the adjusted tentative assessment, ARC's level of assessment, the market value ARC is implying, screening and ranking comparable sales from AROW, and drafting Part D and a requested value. Use this whenever someone mentions grieving or appealing a Nassau property tax assessment, ARC, AROW, an ARC stipulation or settlement offer, a tentative assessed value, or picking comps for a Long Island (Nassau) tax grievance, even if they don't name the form.
---

# Nassau County ARC grievance helper

This skill helps a homeowner prepare a Class 1 residential grievance (AR1) in Nassau County, NY, which they file themselves in AROW (Assessment Review On the Web). The core job is turning the county's numbers into one target figure, then finding honest comparable sales that show the home is worth less than that figure.

Scope: Nassau County Class 1 (1-3 family homes and residential condos) at ARC only. Suffolk County, NYC and commercial property work differently - say so and stop. This is preparation help, not legal or tax advice, and the homeowner files and signs everything themselves.

## Why the math works this way

Nassau assessed value (AV) is a small fraction of market value: **AV = market value x level of assessment (LOA)**, so **market value = AV / LOA**.

There are two LOAs, and the gap between them is the whole reason grievances succeed:

- **The assessor's LOA** is shown on the county property page (0.1% for Class 1). It is applied to values frozen years ago, so it is not the number that matters at ARC.
- **ARC's LOA** is the rate ARC uses to settle. It is lower and falls most years as prices rise while the roll stays frozen. A lower LOA means the same AV implies a *higher* market value, which makes it easier to show over-assessment.

Practitioners often talk about a "multiplier" (for example "AV x 1666"). That is just 1 / LOA. Their decimal notation is often loose (".0060" usually means 0.06%), so always convert from a stated percentage.

## Step 1 - Confirm this season's facts

Dates and rates change every year, and stale figures produce wrong targets. Before doing any math, search for and confirm:

1. **The filing window** for the tax year being grieved. Tax year Y/Y+1 is grieved in roughly January to early March of year Y-1 (for example, the 2028/29 window was set as January 4 - March 1, 2027). Extensions have been common but are never guaranteed, so plan around the published date.
2. **ARC's Class 1 LOA** for that tax year. The most reliable source is page 2 of an ARC Residential Stipulation (form AR 71) for that year, which states the ARC LOA and the higher SCAR LOA. ARC's FAQ page sometimes lists it too. If the current year's rate is not published yet (it usually appears with the first offers, after filing), use the most recent published rate and also show a scenario with a slightly lower one, labelled as a projection.

Historical reference only - verify before use:

| Tax year | ARC LOA | SCAR LOA |
|---|---|---|
| 2024/25 | 0.072% | 0.074% |
| 2025/26 | about 0.066% (unconfirmed - inferred from a single settlement, not a published rate) | - |
| 2026/27 | 0.060% | 0.062% |
| 2027/28 | 0.054% | 0.057% |

## Step 2 - Gather the inputs

Ask for whatever is missing. If browser tools are available, you can read these pages directly; otherwise ask the user to save them as PDFs or screenshots and attach them. Read only - never check boxes, select comps, or submit anything in AROW unless the user explicitly asks for that specific action.

- **County property page, Values tab** (Nassau Land Records Viewer): tentative and prior-year AVs, living area, lot size, year built, school district. Watch the column labels: a column titled "2028 - School ('27-28) and County/Town '28'" is the **2027/28** tax year, not 2028/29. Confirm which year a tentative belongs to before using it.
- **Prior ARC stipulations or determinations** (AR 71): original tentative, "Adjusted Tentative", reduced AV, and the LOA used.
- **AROW "Find Sales" results** - every page. The list can be set to show more rows per page; suggest that so checked boxes are not lost when paging.
- **Purchase price and date** of the home, and anything that hurts value (busy road, flood zone, needed repairs with estimates, unfinished work).

## Step 3 - Work out the starting AV

The AV ARC negotiates from is the **adjusted tentative**, which can differ from the tentative printed on the county notice.

- Class 1 AVs cannot rise more than 6% a year or 20% over five years, except for new construction or renovation.
- If the home won a reduction last year, ARC's adjusted tentative has been observed to be about **last year's reduced AV x 1.06** (the 6% cap applied to the reduced value). This is an observed pattern, not published ARC policy: when the user has a stipulation for the year in question, use the "Adjusted Tentative" printed on it instead, and label any projection as an estimate. The assessor's printed tentative may instead chain off its own earlier tentative (for example 800 -> 848 -> 899) because prior reductions were not yet on the roll when it was published. Explain this so the user is not alarmed by a higher printed number.
- If last year's stipulation was accepted but is not yet final (AROW status "Accepted Stipulation Received"), say the projection assumes it is approved.

## Step 4 - Compute the target

**Target market value = adjusted tentative AV / ARC LOA.** Show it at the confirmed or most recent LOA, and at a projected lower LOA if the current one is not published. Any comparable sale that adjusts below the target supports a reduction.

## Step 5 - Screen the sales

ARC can only consider sold homes - never a neighbour's assessment. Screening matters more than ranking, because the sales that look best on price are often the ones that should not be used.

Exclude, and say why:

- **Pre-construction or teardown sales.** The county record describes the house as it is now, but the sale may have been of an old house or a lot. Flag a sale when: the sale date is before, or within about a year of, the year built; the same parcel appears again at a much higher price; or the price per square foot is far below other homes of the same vintage. Use the later sale of the finished house instead, if listed.
- **Non-arm's-length sales:** foreclosures, short sales, sales between family members, damaged homes.
- **Sales outside the window** AROW or ARC is using for that year. Practitioner guidance is roughly the last two years for other homes; the owner's own purchase may be cited back about three years.
- **A different school district**, unless nothing else is available.
- **The subject home's own row.** AROW lists it but it cannot be selected; mention the purchase in Part D instead, if it falls inside the window and supports a lower value.

## Step 6 - Normalize and rank

AROW's list shows raw prices. Until AROW's own adjusted prices are available (prefer those when they are), normalize by size:

- **Price per sq ft** = sale price / living area.
- **Scaled value** = price per sq ft x the subject's living area.
- **Implied AV** = scaled value x ARC LOA, compared with the adjusted tentative.

Say plainly that this is a rough stand-in: bigger houses usually sell for less per sq ft, so scaling a bigger comp down slightly understates value and scaling a smaller one up overstates it; ARC also adjusts older sales upward for market growth.

Rank the survivors on similarity: living area within about 20%, similar age and style (new construction should be compared with other new builds), similar lot, closeness, and recency. Pick up to five.

Some practitioners recommend using the first five AROW results unchanged, so ARC cannot call the selection cherry-picked. Mention that trade-off, but drop any of those five that fail screening. If fewer than five honest comps support a reduction, say so - and tell the user the home may be fairly assessed, while noting filing is free and ARC cannot raise an assessment because someone filed.

## Step 7 - Present the results

Use this structure:

1. **Target:** adjusted tentative AV, LOA, implied market value (one line each, with any projection labelled).
2. **Comp table:** address, price and date, year built and size, price per sq ft, scaled value, implied AV, and a short verdict (Use / Backup / Weak / Exclude) with the reason.
3. **Bottom line:** average scaled value of the chosen comps, the AV that implies at each LOA scenario, and the reduction that suggests.
4. **Part D draft** (below).
5. **Requested value** (below).
6. **Practical notes:** filing deadline, re-running the sales search if the season has changed, saving PDFs of everything submitted.

### Part D template

> At ARC's Class 1 level of assessment of [LOA]%, my adjusted tentative assessment of [AV] implies a market value of $[target], which this home could not sell for. The attached comparable sales of similar homes in my school district support a market value of about $[comp average], or an assessed value of about [implied AV]. [Purchase: I bought the home on [date] for $[price].] [Condition issues, with estimates or photos uploaded after submitting.] Please revise accordingly.

Fill it only with facts the user has confirmed.

### Requested value (Part B)

ARC never reduces below the value requested, and its own AR1 instructions ask for the lowest market value the applicant deems reasonable. Many filers request well below their comp average (practitioner rules of thumb range from 50% to 60% of it) so the request does not cap the result. Present the comp average and the user's chosen request side by side; the choice is theirs. Do not invent facts to support a lower number - the applicant certifies that what they submit is accurate.

## After filing

ARC sends an offer (stipulation) or a determination, usually many months later. Accepting settles that tax year. Rejecting and going to Small Claims Assessment Review (SCAR) uses a higher LOA, so the same market value becomes a higher AV; an ARC settlement is usually the better result unless the offer is weak. File again every year - reductions carry forward only through the 6% cap.

## Guardrails

- Use only figures read from the user's documents or pages; never estimate a sale price, AV or LOA that was not provided or published. Mark anything inferred (such as a teardown) as an inference.
- Do not file, select, sign, or submit on the user's behalf.
- Personal details (names, address, phone, email) on these documents are private; leave them out of anything the user may share publicly.
- This is general help, not legal or tax advice; for disputes beyond ARC or SCAR, suggest an attorney.

## Worked example (illustrative numbers)

These figures are invented for illustration and do not describe a real property.

Last year's ARC settlement reduced the AV to 800 at an ARC LOA of 0.054%. The adjusted tentative for the next year is about 800 x 1.06 = 848, so the target is 848 / 0.00054 = about $1.57M (about $1.77M if the LOA falls to 0.048%).

The subject is a 2,500 sq ft colonial built in 2020. AROW lists a dozen sales, including:

- A 2024-built home of 2,600 sq ft sold for $1.45M: $558/sq ft, scaled $1.39M, implied AV 753. **Use.**
- The same parcel also appears selling for $650K a year earlier, before the house was finished. **Exclude** as a pre-construction sale.
- A 1985 home of 2,400 sq ft sold for $900K: $375/sq ft, scaled $938K. **Weak** - 35 years older; ARC will adjust heavily for age.

Five honest comps of similar age and size average about $1.42M, which is an AV of about 767 at 0.054% (about 682 at 0.048%) - against an adjusted tentative of about 848, enough to support a reduction.
