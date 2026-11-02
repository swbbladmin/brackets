# Tournament Brackets – How to Use

Each division has its own bracket page. The team count, game dates and known game times are already filled in.

| Division | File | Teams | Games |
|----------|------|-------|-------|
| TeeBall Plus | `teeball-plus-bracket.html` | 10 | 9 |
| 7U | `7u-bracket.html` | 4 | 3 |
| 8U | `8u-bracket.html` | 6 | 5 |
| 9U | `9u-bracket.html` | 7 | 6 |
| 10U | `10u-bracket.html` | 6 | 5 |
| 12U Gold | `12u-gold-bracket.html` | 4 | 3 |
| 12U Silver | `12u-silver-bracket.html` | 3 | 2 |

`index.html` is a menu page that links to all seven.

---

## 1. Put the brackets online (one time)

The whole `brackets` folder is plain files, so any free static host works.

**Easiest: Netlify Drop**
1. Go to **app.netlify.com/drop**.
2. Drag the whole `brackets` folder onto the page.
3. You get a link like `https://something.netlify.app`. That is your menu page.
4. Each bracket is at that link plus its file name, for example `https://something.netlify.app/9u-bracket.html`.

Other options: GitHub Pages or Cloudflare Pages. Upload the folder contents the same way.

You can also skip hosting and just open a file from your computer by double-clicking it. Hosting is only needed so other people can open it.

---

## 2. Set up a division (before the tournament)

1. Open the division's bracket page.
2. Under **Teams**, type each team's name next to its seed. Seed 1 is the top seed. Unused spots become byes automatically.
3. Check each game's **Date**, **Time** and **Field**. Fill in anything blank.
   - Date is a calendar picker.
   - Time is always in 12-hour format. Weekdays offer 6:00 to 9:00 PM. Saturday and Sunday offer 8:00 AM to 8:00 PM.
   - Field is Field 1 to Field 4.
   - If you change a game's date, its time clears so you can pick again.
4. The page title at the top is editable.

> **12U Gold:** Games 1 and 2 have no date yet. Pick one for each.
> **TeeBall Plus, 8U, 10U:** Only dates are filled in for games where you gave a list of times instead of a time per game. Choose each game's time.

---

## 3. During the tournament

1. When a game ends, type each team's **score** in the box at the right of the team name.
2. The team with the higher score turns green and **advances automatically** to the next round.
3. If there is a tie or no score, nobody advances on score. Click a team to advance it by hand (for a forfeit or tiebreaker). Click it again to undo.
4. The champion shows under the bracket when the final is decided.
5. **Clear winners & scores** wipes all scores and winners. It does not clear team names or game times.
6. Changing the **Number of teams** starts that division over (clears scores, winners and game times).

Your changes save in the browser you are using, so reopening the same page on the same device brings them back.

---

## 4. Share the bracket

The pages have no server, so a bracket is shared through a **link that contains the whole bracket**.

1. Finish updating the bracket (names, scores, times).
2. Click **Copy view-only link**.
3. Paste it into GameChanger, a group text or an email.

Anyone who opens that link sees the bracket with scores, times and fields. They can't change anything.

**Important:** a shared link is a snapshot from the moment you copied it. After you enter new scores, click **Copy view-only link** again and send the new one. Old links keep showing the old bracket.

**Copy edit link** makes a link that anyone can edit. Use it only to move your work to another device or hand it to a co-organizer.

Print: the **Print** button prints the bracket without the controls.

---

## 5. Things to know

- Changes are saved per browser and per device. If you switch phones or computers, use the edit link to bring the bracket with you.
- The bracket layout is a standard seeded single-elimination bracket: seed 1 plays the lowest remaining seed, and top seeds get the byes.
- Which numbered game is which matchup comes from that layout. Game numbers and dates were matched to your schedule, so check that the right teams are in the right game slots before sharing.
- If a link ever stops working after a bracket is changed a lot, copy a fresh one. Very long links can break in some apps, and if that happens, share the page address of the hosted bracket plus a screenshot.
