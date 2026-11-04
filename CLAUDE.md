# Project notes for Claude

Read this first. It is the background for this repo, so the user does not have to explain it again.

## Who and what
- **Vyom Mahakali**, a high school student in Irvine, CA. Partner: **Ryan Kim**.
- Goal: get research or shadowing spots in university labs by cold-emailing professors, each with one of our literature reviews attached.
- Vyom's account for everything: **vyommahakali3@gmail.com**. Do NOT use or put files in jadonleelawler@gmail.com.

## Literature reviews (done)
- Six reviews in `literature-reviews/`: Self-Healing Polymers, 4D Printing, Aerogels, Thermoelectric Materials, Hydrogels for Wound Healing, Nanocellulose from Plants.
- Format: "Vyom Mahakali, Ryan Kim" at top, bold title, Abstract, numbered sections, IEEE [n] citations, References. All references were checked against Crossref.
- The user asked not to run them through an "AI humanizer". Don't offer to.

## Google Drive (owned by vyommahakali3)
All professors (62 as of the latest additions) in one sheet, with Topic, PDF to attach, In Gmail Drafts and Sent columns: https://docs.google.com/spreadsheets/d/1yxEAfULbW8NmA57qr1in9n57gX6A96a9WoFJMImPjZE/edit

Professor sheets, one per topic:
- Self-Healing Polymers (9): https://docs.google.com/spreadsheets/d/1mLBljl2zlih5ligwS68TXxdS2l_af5ONn-gTTRaOf-c/edit
- 4D Printing (12): https://docs.google.com/spreadsheets/d/1cjTOKZ0fpj3IDzy_2Q4E27N3UgCr4xjy9yjnOecrnz0/edit
- Thermoelectric Materials (6): https://docs.google.com/spreadsheets/d/1ihGdkgSuysGDo5WYwq2uXBArLGS3CBVgQzUhZnJdc5w/edit
- Hydrogels for Wound Healing (6): https://docs.google.com/spreadsheets/d/1oC_MFE1wnLVjsGVJNIAxe5V5Do3ar7LMpil9lC0RZNE/edit
- Aerogels (1): https://docs.google.com/spreadsheets/d/18k0bAEgaw3dEvCQz8IxigiXasfanwoC_Aq5EwucdEjo/edit
- Nanocellulose from Plants (1): https://docs.google.com/spreadsheets/d/1xzwxP6U_UL4ep0z7zCmeo9UFuBmfpiYHKBcFyV_zywM/edit

Other files:
- All 35 emails, each with an Attachment line: https://docs.google.com/document/d/1rQwZRDvBTiO7l94mPyVm8Wr8LabzsDiOujnohqq81O8/edit
- Resume drafts with placeholders, currently not in use: Vyom https://docs.google.com/document/d/1nz10Fe3sUZWYEzDLIPqqQczKJ3oVcIuMHpu7zi7gBZE/edit · Ryan https://docs.google.com/document/d/1tf-tgnkl_zkI45zRtPMT3ZMxVa3yMWJZivXLd84b5VM/edit

In each sheet, the "Email body" column is a formula built from the "Email template" cell lower down. Edit the template and every email in that sheet updates.

## Rules for professors and emails
- Only professors within about a **40-minute drive of Irvine**: UCI, Chapman, Cal State Fullerton, Cal State Long Beach, Cal Poly Pomona. No UCLA, USC, UC Riverside or UC San Diego.
- Each professor appears in **one topic only** and gets **one email**, which mentions **one** literature review that matches their work.
- Email template: the user's own wording, from Vyom Mahakali, naming Ryan Kim as partner. Subject: "High school students interested in shadowing your lab (<topic>)".
- **No resumes.** The user chose to drop them. The emails say "We have attached a copy of our literature review for your convenience."
- **Never send an email unless the user explicitly says to send it.**
- **Don't commit professor lists, CSVs or emails to this repo.** The user asked to undo that once.

## Sending status
- Gmail Drafts in vyommahakali3 hold 54 drafts: the original 35 plus 19 for professors added later (sheet rows 35–62). **None sent yet.**
- 9 newer professors are held with no draft (no email, no real paper, duplicate paper, or not a professor). The reason is in the sheet's "In Gmail Drafts" column.
- Some newer rows are UC Riverside, which breaks the 40-minute rule above. They were drafted because the user asked for every new row; confirm with the user before sending.
- Zuzanna Siwy (nanocellulose) was dropped from the combined sheet, but her draft is still in Gmail.
- The user attaches the PDFs by hand. The Gmail connector only takes attachments pasted in as base64 (about 280K characters per PDF), so Claude can't reliably attach them. Computer use can't click inside a browser, so it can't do this either.
- Before sending, check: James and Su (4D printing, Cal State Fullerton) have email addresses from old papers, so confirm them on their faculty pages. Kulinsky and Madou are weaker topic matches.
- After the user sends emails, mark them "Yes" in the Sent column of the all-professors sheet and of that topic's sheet.
- Other flags: Wu and Jordan run theory groups. Mohraz and Lee have older email addresses. Siwy is a co-author, not the lead author, on the paper mentioned.

## Connector notes
- Drive, Sheets, Docs and Gmail should all be signed in as vyommahakali3. If an edit to one of these files returns "permission denied", that connector is probably signed into the wrong account. Ask the user to reconnect it in claude.ai connector settings.
