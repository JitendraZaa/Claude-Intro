# Reminder email: Build Your First AI Assistant

## Before sending

48 people are registered, but the event site has **43 places**, so 5 people are on the waitlist. That is why this file has two versions of the email. Sending version 1 to all 48 would tell the 5 waitlisted people they have a seat.

Check these first:

- [ ] **Lunch.** Entry is free, but nothing says whether lunch is provided, so the email only mentions the lunch break. If you are providing lunch, add a line about it.
- [ ] **Laptops.** 27 registrants said they need a laptop, and neither room provides them. The email asks those people to reply, so plan how you will answer.
- [ ] Send with every address in **BCC**, not To, so registrants can't see each other's email addresses.

---

## Version 1: people with a seat

**Subject:** Reminder: Build Your First AI Assistant, Saturday 21 November

Hi {first_name},

Thanks for registering for **Build Your First AI Assistant**. Your seat is confirmed, and here is everything you need for the day.

**When:** Saturday 21 November 2026, 9:30 to 16:00. Doors open at 9:00.
**Where:** Community centre, Room B
**Cost:** Free

**The day**

| Time | Session | Led by |
|---|---|---|
| 9:30 | Welcome and setup | |
| 10:00 | What an AI assistant can do for you | Alex Carter |
| 11:00 | Hands-on: your first project in Claude | Alex Carter |
| 12:30 | Lunch | |
| 13:30 | Hands-on: build a small web page with Claude Code | Sam Brooks |
| 15:00 | Show and tell | |
| 15:45 | Wrap-up and next steps | |

**What to bring**

- **A laptop, if you can.** Both hands-on sessions are done on a laptop, and wifi is provided. If you told us you don't have one, please reply to this email so we can talk about options.
- Please arrive by 9:15 so you have time to get on the wifi before we start at 9:30. Doors open at 9:00.

**Can't make it any more?** Please reply and let us know. The workshop is full, so we can offer your seat to someone on the waitlist.

See you on the 21st,
[YOUR NAME]

---

## Version 2: people on the waitlist

**Subject:** Build Your First AI Assistant: you're on the waitlist

Hi {first_name},

Thanks for registering for **Build Your First AI Assistant** on Saturday 21 November 2026. The workshop filled up before your registration came in, so you don't have a seat yet. You are **number {waitlist_position} of 5** on the waitlist.

If a seat becomes free, we will email you right away. It may be worth keeping the day open: 9:30 to 16:00 in Room B at the community centre, with doors opening at 9:00.

If you no longer want a place, just reply and we will take you off the list.

Thanks for your patience,
[YOUR NAME]

---

## Recipients

From `seating.csv`, the final seat list. There are 43 places: Room B has 45 seats, and 2 are kept for the speakers. Seats go in order of `registered_on`. People who registered on the same day keep their order from `registrations-export.csv`. All 48 people are covered.

**Version 1: seat confirmed (43)**

```
rowan.knight@example.com, casey.grant@example.com, skyler.grant@example.com, finley.bennett@example.com, cameron.shaw@example.com, avery.porter@example.com, jamie.knight@example.com, sage.price@example.com, finley.cole@example.com, alex.lane@example.com, alex.fisher@example.com, skyler.wade@example.com, finley.ellis@example.com, alex.nash@example.com, sam.gray@example.com, rowan.fisher@example.com, finley.foster@example.com, parker.marsh@example.com, jordan.morgan@example.com, riley.hughes@example.com, alex.morgan@example.com, rowan.carter@example.com, alex.ellis@example.com, sage.stone@example.com, elliot.morgan@example.com, jamie.cole@example.com, dana.shaw@example.com, jamie.shaw@example.com, parker.knight@example.com, reese.shaw@example.com, cameron.price@example.com, reese.wells@example.com, rowan.brooks@example.com, rowan.ellis@example.com, blake.price@example.com, sam.foster@example.com, riley.price@example.com, quinn.porter@example.com, morgan.gray@example.com, robin.lane@example.com, sam.price@example.com, drew.gray@example.com, sam.porter@example.com
```

**Version 2: waitlist (5)**

Each person's email shows their own place on the waitlist, so send these one at a time (or as a mail merge) rather than as a single BCC.

| Waitlist place | Name | Email |
|---|---|---|
| 1 | Reese Lane | reese.lane@example.com |
| 2 | Sage Hart | sage.hart@example.com |
| 3 | Sage Bennett | sage.bennett@example.com |
| 4 | Emerson Knight | emerson.knight@example.com |
| 5 | Casey Nash | casey.nash@example.com |
