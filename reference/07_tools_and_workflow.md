# Tools and Workflow

No logins, passwords, or access links live in this folder. Access comes from the owner. Never ask for or accept a password in chat.

## The path a lead takes

```
County PDF/CSV -> Scout Engine (clean and classify) -> BatchLeads (upload and enrich)
-> Badger Maps (routes for door knocking) -> Door Knock / Call / Text -> Appointment -> Deal
```

A setter works near the right end of that line: calling, texting, and setting appointments from leads that have already been cleaned and ranked.

## What each tool is for

| Tool | What it does | Setter touches it? |
|---|---|---|
| Scout Engine | Cleans raw county lists and sorts leads into Gold / Silver / Bronze / Pending | No. Runs behind the scenes. |
| BatchLeads | Adds phone numbers and emails to leads (enrichment) | Possibly for contact info. Owner confirms. |
| Badger Maps | Plans door-knocking routes | Mostly the door-knockers, not callers |
| Lead tracking (status tags, Airtable) | Where each lead's status and notes are recorded | Yes. Every contact gets logged. |

**Calling time is tracked in Go High Level or Salesforce.** Setters' calls, notes, and appointments are logged there. Which one a specific setter uses is set by the owner.

**Not confirmed in this folder:** how a setter gets access to Go High Level or Salesforce, how call recordings are stored, and what the dialer setup is. See `12_not_covered.md` and ask the owner.

## Manual checkpoints (important)

Human review is required before: uploading to BatchLeads, uploading to Badger Maps, contacting a homeowner when a lead is flagged for review, making an offer, sending a deal or fee agreement to a buyer, or removing a lead permanently. Automation produces reviewable output. It does not silently take irreversible action.

For a setter this means: Pending / Manual Review leads are not called until reviewed, and you do not decide to delete a lead.

## Log everything

Every contact attempt and every result gets recorded. That includes calls that go to voicemail. If it is not logged, the next person has no idea what happened.

What to capture when you do speak with a homeowner (this mirrors the intake form):

- Name, best phone, best email, property address, county.
- Is the home owner-occupied?
- Is there a sheriff sale date? What is it?
- Do they want to keep the home or sell, or are they not sure?
- Is anyone already helping (an attorney, housing counselor, lender)?
- Who else is involved in the decision?
- Best time to reach them.
- The agreed next step.

The setter's job is to get the basics and set the appointment. The detailed numbers (balance, reinstatement amount, repairs, liens) are for the closer's appointment.

## Handling sensitive data

Homeowner names, addresses, phone numbers, and amounts owed are sensitive. Keep them in the company's tools. Do not paste real homeowner details into a chat, a text to a friend, or anywhere public.
