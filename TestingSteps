# Staging browser testing guide

This guide is for a first-time tester using the staging website. It walks through the three book formats, page review, quality checks, and optional exports, then provides a feedback form.

**Staging website:** <https://staging-app.rraisreads.com/>

Use only staging. Do not enter real personal information, publish the test books, or submit staging files to Amazon KDP or another store.

## 1. Before you start

### Get approval for provider costs

Ask the project owner whether you are approved to generate drafts, artwork, covers, or use research features. Saving a brief does not start generation or consume generation credits. Generation, cover/art generation, retries, and research may call paid external providers. Staging's credit bypass does **not** prevent those charges.

- If the owner has not approved provider usage, complete the navigation and brief-saving checks only. Do not click **Generate Book Draft**, **Generate art**, **Generate cover**, research buttons, or export approval controls. Mark the generation-dependent cases **BLOCKED — provider spending not approved**.
- If approved, generate each test book once. If a request looks stuck or fails, wait and record the message before retrying. Do not repeatedly click a generation button.
- The **Deterministic puzzles** option describes how puzzle content is produced; do not treat it as a promise that the rest of the workflow has no provider or infrastructure cost.

### Prepare

1. Use a current version of Chrome, Edge, Firefox, or Safari on a device connected to the Wi-Fi network authorized for staging.
2. Open the staging website above. Check the address bar says `https://staging-app.rraisreads.com/`.
3. Keep this guide open in another tab or print it.
4. Use new, disposable project names such as `QA 2026-11-27 Storybook`. Replace the date with the day you test. Do not edit the existing sample project.
5. Have a way to take screenshots. Before sharing a screenshot, check that it does not show private information, browser passwords, cookies, or a signed download URL.
6. Record the date, approximate time, device, operating system, browser, and whether you used Wi-Fi, VPN, or cellular data.

## 2. How to record results

Give each test one result:

- **PASS** — the expected result happened.
- **FAIL** — it did not happen, or the result was visibly wrong.
- **BLOCKED** — you could not safely continue, for example because provider spending was not approved or staging was unavailable.
- **NOT RUN** — you did not attempt the test.

For a failure, write down the test number, what you clicked, what you expected, what happened instead, and the exact error text. Attach a screenshot if possible. Do not keep clicking or retrying after an error.

## 3. Test the website and navigation

### TEST-01 — Open the site and find the three book formats

1. Open <https://staging-app.rraisreads.com/>.
2. Confirm the page loads without a browser warning or an error page.
3. Scroll to the section titled **One studio. Three ways to create.**
4. Confirm the cards **Storybooks**, **Coloring books**, and **Activity books** are visible.
5. Click **Create this book** on each card in turn. Confirm each opens the Studio with the matching book type selected:
   - Storybooks → **Storybook**
   - Coloring books → **Coloring Book**
   - Activity books → **Puzzle & Activity Book**
6. Return to the homepage between checks using the browser Back button or by entering the staging website address again.

**Expected:** All three cards are visible, their links open the Studio, and each selects the correct book type.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-02 — Check the main pages

1. Open `/projects` by entering `https://staging-app.rraisreads.com/projects` in the address bar. Confirm the Projects page loads.
2. Open `/studio` by entering `https://staging-app.rraisreads.com/studio`. Confirm the Studio loads.
3. Open `/terms` and `/privacy` the same way. Confirm each page loads and contains readable content.
4. Use the browser Back button once, then Forward once.
5. If any page fails, note its full address and the browser's exact error or status.

**Expected:** Projects, Studio, Terms, and Privacy load; Back and Forward navigation work.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-02B — Save a brief and reopen it

1. Open `/studio` and create a disposable project with a unique project name. You can use any of the three book types.
2. Fill the required brief fields, then click **Save & Continue to Generation →**. Do not click **Generate Book Draft**.
3. Click **View all saved projects →**.
4. Find the project you just named and click **Open saved brief**.
5. Confirm the project name and the settings you entered are still present.

**Expected:** The saved brief appears in Projects and can be reopened with its settings intact. No draft is generated.

**Result:** `_____`  **Notes:** `________________________________________`

## 4. Shared steps for creating a book

Repeat these steps for each test project. The next sections provide the specific values to enter for each format.

1. Open the matching format card on the homepage, or open `/studio` and select the matching option under **Book type**.
2. Enter the test's unique value in **Project name**. Keep the project's name different from any existing sample.
3. Fill in the requested brief fields from the test case. Leave **Optional Strategy Accelerator** closed and unused; its research buttons may call an external provider.
4. Click **Save & Continue to Generation →**.
5. Confirm the brief is saved. The Studio says saving the brief does not start generation.
6. If provider spending is approved, click **Generate Book Draft (N pages) ✨** once and wait for the request to finish. The label may change to **Generating your draft...** while it works.
7. If generation is not approved, stop after saving the brief and mark the generation/review steps **BLOCKED**.
8. Do not refresh, close the tab, or click Generate a second time while a request is still working. If an error appears, capture the exact message and stop that test.

## 5. Storybook tests

Create a separate project for each storybook format you are approved to generate. The three format options are **Plain / text-led storybook**, **Color illustrated storybook**, and **Full-color picture book**. The first is a text-only layout; the other two include illustrations. Each generated project may incur provider costs.

Use these shared, child-friendly sample details:

- **Age group:** 4–7
- **Language:** English
- **Trim size:** 8.5x8.5
- **Story brief:** `Mira, a small rabbit, helps her friend find the way home by sharing a lantern. The story is gentle, reassuring, and shows that asking for help can build friendship.`
- **Character reference:** `Mira is a small silver rabbit with a yellow scarf. Keep her appearance consistent on every page.`
- **Intended audience / buyer:** `Adults choosing a gentle read-aloud story for children ages 4–7.`
- **Reader benefit / learning outcome:** `Asking for help builds friendship.`

### TEST-03A — Plain / text-led storybook

1. Start a Storybook project named `QA <date> Storybook Text-led`.
2. Set **Storybook format** to **Plain / text-led storybook**.
3. Set **Story sections** to `2` and **Chapter / section groups** to `1`.
4. Enter the shared sample details above. Select a language and trim size as above.
5. Save the brief, then generate once if approved.
6. In Review Studio, use **‹ Prev**, **Next ›**, or the page selector to read every page.

**Expected:** The project is text-led, with readable story copy and no requirement for generated page artwork. The story is understandable, age-appropriate, and has a beginning, middle, and ending. Note that long story sections may continue onto additional PDF/EPUB pages.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-03B — Color illustrated storybook

1. Start another Storybook project named `QA <date> Storybook Illustrated`.
2. Set **Storybook format** to **Color illustrated storybook**.
3. Set **Story spreads** to `2` and **Chapter / section groups** to `1`.
4. Enter the shared sample details above. Keep the selected illustration direction or choose one you prefer.
5. Save the brief, then generate once if approved.
6. Review every spread and its facing pages.

**Expected:** Story text and color illustrations appear together; Mira's appearance remains consistent; text and pictures agree with each other; important text and artwork are not clipped at the page edges.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-03C — Full-color picture book

1. Start another Storybook project named `QA <date> Storybook Picture`.
2. Set **Storybook format** to **Full-color picture book**.
3. Set **Story spreads** to `2`.
4. Enter the shared sample details above.
5. Save the brief, then generate once if approved.
6. Review every spread and verify the cover and interior use a consistent visual style.

**Expected:** The story is presented as a full-color picture book; page art and story beats correspond; text is readable and not hidden or cut off. Report any difference you notice from the Color illustrated storybook.

**Result:** `_____`  **Notes:** `________________________________________`

### Storybook observations

For each project, note whether the story reads naturally aloud, whether words fit the intended age, whether the same character stays visually consistent, and whether text is legible against its background. Report spelling, grammar, cultural, or continuity concerns with the page/spread number.

## 6. Coloring book test

### TEST-04 — Coloring pages and color references

1. Start a Coloring Book project named `QA <date> Coloring`.
2. Set **Age group** to `6-8`. Confirm **Coloring layout** is **Line art with color-reference inset (ages 6–8)**. If changing the layout changes the age group, use the matching 6–8 option.
3. Set **Language** to English, **Trim size** to 8.5x11, and **Page count** to `2`.
4. Enter these values:
   - **Coloring theme and subjects:** `Friendly garden animals: one rabbit watering flowers and one bird near a nest. Keep each page cheerful and simple, with large shapes and no words or lettering.`
   - **Page composition:** `single subject`
   - **Line-art style:** `Simple bold coloring-book outlines`
   - **Intended audience / buyer:** `Adults choosing an easy coloring activity for children ages 6–8.`
   - **Coloring focus:** `Creativity and fine-motor practice`
5. Save the brief, then generate once if approved.
6. Review both pages. If approved for additional artwork-provider usage, use **Generate missing art/references** or **Generate color reference** only when an expected image/reference is missing. Do not use **Re-roll art** just to explore alternatives.

**Expected:** Each coloring page has clean, dark, closed outlines on a light background, a clear main subject, and enough open space to color. The inset color reference should correspond to its line-art page when generated. Check that the inset does not obscure the drawing and that no unwanted words, signatures, or colored fills appear in the line art.

**Result:** `_____`  **Notes:** `________________________________________`

## 7. Puzzle & Activity Book test

### TEST-05 — Activities and solutions

1. Start a project named `QA <date> Activity`.
2. Set **Book type** to **Puzzle & Activity Book**.
3. Set **Age group** to `6-8`, **Language** to English, **Trim size** to 8.5x11, and **Page count** to `3`.
4. Enter:
   - **Activity theme:** `A friendly garden adventure with rabbits, birds, flowers, and butterflies. Use simple, familiar words and child-safe instructions.`
   - **Activities to include:** select **Mazes**, **Counting**, and **Matching**. Clear other selections for this small test.
   - **Activity difficulty:** **Gentle**
   - **Puzzle content source:** **Deterministic puzzles**
   - **Pair shorter activities on each page:** leave unchecked for this test
   - **Intended audience / buyer:** `Adults choosing a gentle activity book for children ages 6–8.`
   - **Skills to practice:** `Counting, observation, and problem solving`
5. Save the brief, then generate once if approved.
6. Review all activity pages. Read the instructions and attempt each activity yourself.
7. Record whether each activity is solvable and whether **Run content QA** reports any missing solutions. If export testing is approved, check **Include puzzle solutions in the interior (adds answer pages and affects KDP page count)** and verify the answers in the exported interior. Do not approve an export unless export testing has been approved.

**Expected:** Instructions are clear and age-appropriate; each maze has a valid route; counting and matching tasks have unambiguous answers; any provided solutions match the activities. The activities should be readable and fit within their pages. Report any activity that cannot be solved or whose answer key is incorrect.

**Result:** `_____`  **Notes:** `________________________________________`

## 8. Review Studio checks

Complete these on one disposable generated project only, and only if generation is approved.

### TEST-06 — Read, edit, and navigate pages

1. Open each page/spread using the page list, **‹ Prev**, **Next ›**, and the page selector.
2. Confirm the page counter changes and the displayed page matches the selection.
3. In **Page Inspector**, make a small, reversible edit to **Story text**, **Activity instructions**, or **Page notes**, depending on the book type.
4. Click outside the text box and wait for **Saving page...** to disappear. If an error appears, record it.
5. Use **Undo**, then **Redo**, and confirm the edit changes accordingly.
6. If you also test page ordering, use the up/down arrows on a page card and then restore the original order. Do not delete a page unless the project is disposable and you are willing to leave it changed.
7. Use **Back to brief**, then **Return to Review Studio →** if shown. Confirm the edited content remains.

**Expected:** Page selection works, edits save, Undo/Redo work, and the page order can be changed and restored without losing content.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-07 — Book details, content quality, and print preflight

1. Click **Book & export**.
2. Check the displayed book title and subtitle. Do not click **Save title and generate cover**, **Generate cover**, **Regenerate cover**, or **Refresh title and subtitle ideas** unless their provider usage is approved.
3. Click **Run content QA**. Read any warnings/errors and compare them with your own review. Automated checks do not replace a human read-through.
4. Click **Run print preflight**. Record its status and any findings, including authored, designed, and KDP interior page counts.
5. For Puzzle & Activity Books, inspect the answer-key checkbox and note whether answer pages affect the KDP page count as described.
6. Close the panel when finished.

**Expected:** The title and book details correspond to the selected project; QA and preflight complete or show a clear error; warnings are visible and understandable. Preflight is not a replacement for KDP Previewer or a physical proof.

**Result:** `_____`  **Notes:** `________________________________________`

### TEST-08 — Optional export and downloaded files

Only continue if the project owner has approved export testing. Exports approve the book and prepare files; do not publish or sell them.

1. In **Book & export**, select only the formats the owner asked you to test under **Formats to prepare**. Options include **KDP Interior PDF**, **Cover Wrap PDF**, **EPUB 3**, **Reader PDF**, and **KDP package (ZIP)**.
2. Resolve any blocking message. Do not bypass missing artwork, cover, title confirmation, or other readiness checks.
3. Click **Approve & prepare** once and wait. Do not click again while it is working.
4. Use each **Download ...** link that appears. Open the downloaded file with an appropriate reader/archive program.
5. Check that the file opens, has the expected title and pages, and is not blank, truncated, or corrupt. For the KDP ZIP, confirm it contains the files indicated by the package contents.
6. Record the format and any issue. Do not share the download URL; it may be temporary and contain a private token.

**Expected:** The approved format(s) produce downloadable, readable files with content matching the reviewed book. Record actual preflight warnings and any layout differences; passing preflight does not certify KDP acceptance.

**Result:** `_____`  **Notes:** `________________________________________`

## 9. Small-screen check

### TEST-09 — Use Studio on a phone or narrow browser window

1. Open the homepage and Studio on a phone or make the browser window narrow.
2. Check that the three format cards, form controls, buttons, and text can be read without sideways page scrolling.
3. If a generated project is available, open Review Studio. Check page navigation and tap **Page tools** to show the page inspector.
4. Check that the page controls and **Book & export** button remain usable. Do not generate or export another project just for this check.

**Expected:** Navigation, page review, and controls remain visible and usable on the device. Note any control that is hidden, cut off, too small, or difficult to tap.

**Result:** `_____`  **Notes:** `________________________________________`

## 10. Feedback to send the project owner

Copy this section once for each book you tested. Attach screenshots only after checking for private information and signed URLs.

```text
Tester:
Date and approximate time:
Device / operating system:
Browser and version (if known):
Network (Wi-Fi / VPN / cellular):
Staging address:
Project name:
Book type and storybook format (if applicable):
Test result (PASS / FAIL / BLOCKED / NOT RUN):

What worked well:

What was confusing or difficult:

Story/content feedback (include page or spread number):

Illustration/coloring/activity feedback:

Page layout, readability, or print concerns:

Exact error text, if any:
Steps immediately before the issue:
Screenshot filename(s):

Would you use this format again? Why or why not?
What is the one change that would improve this book most?
```

### Overall summary

| Test | Result (PASS / FAIL / BLOCKED / NOT RUN) | Main feedback |
|---|---|---|
| TEST-01 — Format cards |  |  |
| TEST-02 — Main pages |  |  |
| TEST-02B — Saved brief |  |  |
| TEST-03A — Text-led storybook |  |  |
| TEST-03B — Color illustrated storybook |  |  |
| TEST-03C — Full-color picture book |  |  |
| TEST-04 — Coloring book |  |  |
| TEST-05 — Puzzle & Activity Book |  |  |
| TEST-06 — Page review and edits |  |  |
| TEST-07 — QA and print preflight |  |  |
| TEST-08 — Optional exports |  |  |
| TEST-09 — Small-screen use |  |  |

Send the completed feedback and approved screenshots to the project owner. Do not include passwords, credentials, cookies, signed URLs, or real children's personal information.
