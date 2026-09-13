# North's Warden Sentencing Tool
A sentencing tool for Warden players on SS14's Funky Station. No more math with a prisoner and their lawyer staring at you.

What it does:
* Browse or search the full Space Law crime list, sorted by degree.
* Click to stack charges onto a running charge sheet.
* Adjust each charge for repeat offenses (1st, 2nd, 3rd, 4th+).
* A severity slider snaps between minimum and maximum across every stacked charge.
* Automatic permanent-confinement flag once a sentence crosses 20 minutes, straight from the guidebook.
* Special-case handling for Degree V crimes with non-numeric sentences (Permanent, Execution, etc).
* A pie chart breakdown of which charges are driving the sentence.
* A procedural obligations checklist that updates with the station's alert level.
* Hover-for-info tooltips with the exact guidebook wording for every crime.
* Time-served tracking.

# How was this made?
Full transparency: I built this with AI assistance, start to finish. I have zero coding experience and, frankly, zero interest in getting any. I'm a marketing guy who likes making things that are actually useful for people to use. The crime data and sentencing logic come from Funky Station's Space Law guidebook, the design decisions are all mine, and the code itself came out of a conversation with Claude.

If that's not your thing, no hard feelings. I'd rather be upfront about it than pretend otherwise, though.

# Licensing
None. Do whatever you want with this! use it, modify it, redistribute it, no attribution needed.
