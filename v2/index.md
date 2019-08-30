---
title: Get Started with the Cap Table and Exit Waterfall Tool
lede: 'An overview of the free <a href="/cap-table">Cap Table and Exit Waterfall Tool</a>.'
---
The goal of this model is to show how to build a cap table and an exit waterfall, for a variety of situations, plus provide a working capital table to use for (almost) all situations. The Cap Table, Assumptions, Exit Waterfall, and Summary sheets comprise the working capitalization table to use for your business, the rest of the sheets are instructional tools to cover specific situations around building and managing cap tables. [^1]

## How it works

The core working cap table is comprised of four sheets - Cap Table, Assumptions, Summary, and Exit Waterfall - that provide an integrated cap table and exit waterfall that handle a wide variety of situations.

- Cap Table is the default, fully-featured Cap Table that has the full range of features explained in the instructional sheets 1 through 3 already built in. This is the model you can use to outline your cap table through a number of rounds and situations.
- Assumptions provides the details on the rounds used by the Cap Table and Exit Waterfall Sheets
- Summary is a print-ready, summary of the fully-diluted cap table that you can easily edit to show the round(s) of your choosing. It pulls data from the Cap Table based on your selections.
- Exit Waterfall uses the Cap Table and the assumptions for each round to show how the different share classes on the cap table earn proceeds at different exit valuations.

The rest of the sheets are a set of instructional sheets:

- 1 - Equity Issuance is an example cap table that demonstrates a simple issuance of a first round of equity
- 1 - Equity Issuance Round 2 is an example cap table that builds on the first issuance to show what happens with a second round of equity
- 2 - Premoney Option Pool demonstrates creating an option pool in the premoney (explanation on the sheet)
- 2 - Postmoney Option Pool demonstrates creating an option pool in the postmoney (explanation on the sheet)
- 2 - Option Pool, 2nd Round demonstrates how an option pool is added to in a second round of financing, and is built to handle both premoney and postmoney option pools
- 3 - Convertible Issuance demonstrates issuing a new convertible note.
- 3 - Conversion, Premoney demonstrates converting a convertible instrument at the next round using the premoney method (v1 of the Cap Table Tool only used this method)
- 3 - Conversion, % Ownership demonstrates converting a convertible instrument at the next round using the percentage ownership method
- 3 - Conversion, $ Invested demonstrates converting a convertible instrument at the next round using the dollars-invested method
- 4 - Exit Waterfall Distribution uses the Option Pool, 2nd Round cap table to show how the shareholders earn proceeds at different valuations based on a variety of assumptions about the terms of their shareclasses. This is the most detailed and most complex part of the instructional sheets.
- 5 - VC Valuation is a separate tool, not connected to the other instructional sheets, that creates a probability-weighted valuation and IRR forecast for a given investment

## How to use the tool

A few things to remember in using the tool:

1. Use the Assumptions sheet to provide the setup for the core Cap Table and Exit Waterfall.
2. Any number in blue with grey shaded background is an input (i.e. an assumption or data point that can be changed), anything in black is the result of a formula. Change blue at will, change anything in black with caution (know what you are doing)
3. All cells and formulas are unlocked - as in all Foresight models - so that you can make edits as needed and completely understand what is going on.
4. The sheets are extensively noted to provide context, detail, and instructions on what the terminologies mean and how to use the model.
5. All assumptions are illustrative ONLY, do not assume they are market data or standard unless specifically noted
6. Notes on what's changed in versions of the template are on the "Changelog" sheet.
7. Note: There are a couple "yes/no" dropdowns for turning on circular references in a couple sheets. Essentially, I build models to not require circulars, but some calculations on cap tables require iterative calculations (i.e. the calculation is based on something referring to the calculation), so to do this you must turn on iterative calculations in Excel / Google Sheets to handle the calcs. The formulas are written so that there is a non-iterative variation, but for some situations you will need to turn on circular references to get the exact calculation. By default, these flags are "no" so that you do not get a note about circular references in the model.

A couple simplifying assumptions are built into the model.

1. Prorata for existing investors into future rounds is an input, not calculated
2. Down rounds or recapitalizations will require some restructuring for the appropriate recap round and any anti-dilution provisions.
3. Waterfall analysis assumes that each stage of equity has seniority over earlier rounds.

The best way to start using the cap table is to start inputting the assumptions for your known rounds on the Assumptions and Cap Table sheet, and then if desired start inputting projected rounds to see their full impact on ownership, dilution, and value. Once you have that setup, go to Exit Waterfall and, if necessary, adjust the pre-distribution cap table and any liquidation preference assumptions.

If you get stuck on anything, that's the perfect time to check out the relevant instructional sheet, which are by design built to be simpler to understand and follow. I've also created additional demo videos for the instructional sheets:

- [How to create an option pool](/learn/cap-table-option-pool)
- [How to convert convertibles and calculate share prices](/learn/cap-table-conversion)
- [How to create an exit waterfall showing a distribution of proceeds](/learn/cap-table-waterfall)
- [How to use the Venture Valuation Tool](/learn/venture-valuation)

## Should I use this to manage my cap table?

As a reminder, this model is created to be a sample cap table to help you understand how a cap table works, and how ownership is impacted by investment rounds and valuations. Once you're running a company, I highly suggest using an online cap table management platform, such as:

- [Carta](https://carta.com/)
- [Captable](https://captable.io/)
- [Capshare](http://www.capshare.com)

The realities of managing a cap table through all different investment terms, option grants, exercises, conversions, and more, can be daunting and it can be easy to make simple errors with meaningful impacts. Through early rounds it's fine to manage the numbers with a spreadsheet, but the online tools do a great job of managing the numbers and add on a number of features that make managing the practicalities and paperwork involved much easier.

[^1]: One of the major changes I made in v2 of the Cap Table tool was to improve on the instructional side of v1 - meaning, v1 worked, but it didn't really explain why the cap table worked that way. For v2, I wanted to show a lot more examples, particularly because for many people building your own cap table specific to your situation is the right way to do it. The default Exit Waterfall, in fact, can take editing to make it fit your situation depending on how you use the default Cap Table itself. It's complicated, and in real life we often have unique situations or corrections that are almost impossible to build into a useable spreadsheet template without an wide array of setup features that would be unused by the vast majority of people. So, you may need to build your own cap table and exit waterfall from scratch - and thus, that's why I built the instructional sheets to help you build your own.
