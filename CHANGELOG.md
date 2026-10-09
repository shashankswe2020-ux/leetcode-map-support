# What's new in LeetCode Map

Changes in each version of the extension, newest first. Chrome updates the extension for you; to check your version, open `chrome://extensions` and look under LeetCode Map.

## 1.2.2 (9 October 2026)

**Easier to read**
- The popup is less crowded: a smaller progress meter, a shorter explanation under **Next**, and more room for long problem titles.
- Busy maps show at most six problems per column, with fewer crossing lines. Every related problem is still in the List view.

**Solved problems sync from LeetCode**
- If you're signed in to LeetCode, the problems you've solved there are marked automatically, so **Unsolved only** works without ticking everything by hand.
- Problems you mark yourself are kept. If you're signed out, or the sync fails, the popup tells you and manual marks keep working.

## 1.2.1 (9 October 2026)

**A new look**
- The popup has been redesigned. Light mode looks like engineering paper and dark mode like a slate board, and it follows your system setting. There are new icons too.
- The map is drawn like a notebook sketch: difficulty is shown with highlighter colours, each layer has a handwritten label, and a line is inked from your problem to the one you're looking at.

**Know what to solve next**
- **Next** now tells you why a problem was picked, for example "88% similar to Two Sum. Both use Array and Hash Table." Use **Skip** to see another suggestion.
- Problem details appear only when you click a problem, so the current problem isn't shown twice.
- Each difficulty filter shows how many problems it covers.

**Faster**
- The map only redraws when something changes, instead of animating constantly.

The **Buy me a coffee** button is now a quieter **Support the project** link at the bottom.

## 1.2.0 (14 September 2026)

**More reliable**
- Search no longer holds up the map. The map for the problem you're on appears as soon as it's ready.
- **Retry** reloads everything at once, and doesn't replace a problem you've just picked.
- A problem you choose from search is no longer swapped for the tab you're on while the popup is still starting.
- Marking problems solved quickly no longer gets out of step. A failed save never loses problems you'd already marked.

## 1.1.0 (11 September 2026)

**Find any problem**
- Search by number or title from any tab, not just LeetCode.
- Switch between the map and a list you can use with the keyboard.

**Explore a problem**
- Click a problem on the map to see its difficulty, its similarity score and the topics it shares with yours, then open it.
- Mark problems solved with a checkbox. Problems you'd already marked are kept.
- **Next problem** opens an unsolved suggestion and respects your difficulty filters.

**Works offline**
- Your 20 most recent maps are saved, so you can open them offline. The popup shows when each one was saved.
- The popup shows when the problem data was last updated, and you can retry a failed load without reopening it.

**Smaller fixes**
- Long titles fit better, keyboard focus is easier to see, and animation is reduced if your system asks for less motion.

## 1.0.0 (30 May 2026)

**First release**
- A map of the problems most similar to the one you're on, from Easy to Hard.
- Problems are matched on what they ask you to do, not just their tags.
- Filter by difficulty, mark problems solved, and hover a problem to see its similarity score.
- Open any suggested problem in one click.
