# Bail bond bounties

**Source:** `bailbond1.c` through `bailbond4.c` (~930K each),
`bailbond_launcher.c` (264K), `postkilled_bailbond2.c`

Four complete bounty targets plus a launcher that gates availability.

A ready-made bounty job structure: target selection, tracking, capture-or-kill
branching, and payout. The launcher is the piece worth reading first — it shows
how R* decides when a bounty becomes available.
