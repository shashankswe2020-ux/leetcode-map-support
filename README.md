<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="LeetCode Map: see the problems near the one you're on." src="assets/banner-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/leetcode-map/hbponnlnmcomlbplhcbhfaeckbnngdim"><img alt="Chrome Web Store version" src="https://img.shields.io/chrome-web-store/v/hbponnlnmcomlbplhcbhfaeckbnngdim?label=version&labelColor=1F2523&color=00A693"></a>
  <a href="https://chromewebstore.google.com/detail/leetcode-map/hbponnlnmcomlbplhcbhfaeckbnngdim"><img alt="Chrome Web Store users" src="https://img.shields.io/chrome-web-store/users/hbponnlnmcomlbplhcbhfaeckbnngdim?label=users&labelColor=1F2523&color=C98A00"></a>
  <a href="https://chromewebstore.google.com/detail/leetcode-map/hbponnlnmcomlbplhcbhfaeckbnngdim/reviews"><img alt="Chrome Web Store rating" src="https://img.shields.io/chrome-web-store/rating/hbponnlnmcomlbplhcbhfaeckbnngdim?label=rating&labelColor=1F2523&color=E8264F"></a>
</p>

<p align="center">
  <a href="https://chromewebstore.google.com/detail/leetcode-map/hbponnlnmcomlbplhcbhfaeckbnngdim"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-install-dark.svg"><img alt="Install from Chrome Web Store" src="assets/btn-install-light.svg" height="44"></picture></a>&nbsp;
  <a href="https://github.com/shashankswe2020-ux/leetcode-map-support/issues/new?template=bug_report.yml"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-bug-dark.svg"><img alt="Report a bug" src="assets/btn-bug-light.svg" height="44"></picture></a>&nbsp;
  <a href="https://github.com/shashankswe2020-ux/leetcode-map-support/issues/new?template=feature_request.yml"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/btn-idea-dark.svg"><img alt="Suggest a feature" src="assets/btn-idea-light.svg" height="44"></picture></a>
</p>

LeetCode Map is a Chrome extension for practising on LeetCode. Open a problem, click the icon, and it shows you the problems that use the same idea: easier ones to warm up with when you're stuck, and harder ones to try once you've solved it.

This repository is where you report bugs and ask for features. The extension's source code isn't public.

## What's new in 1.2.2

- **Solved problems sync from LeetCode.** If you're signed in, the problems you've solved there are marked automatically, so **Unsolved only** just works.
- **A calmer popup.** Less clutter, more room for long titles, and at most six problems per column on busy maps.
- **New look in 1.2.1:** paper and slate themes, a notebook-style map, and a **Next** suggestion that says why it was picked.

See every version in the [changelog](CHANGELOG.md).

## How it works

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/how-it-works-dark.svg">
  <img alt="Diagram of the map: easy and medium layers on the left, the current problem in the middle, medium and hard layers on the right. The most similar problems sit at the top of each layer, and bigger nodes are more similar." src="assets/how-it-works-light.svg" width="100%">
</picture>

1. Open any problem on [leetcode.com](https://leetcode.com/problemset/).
2. Click the LeetCode Map icon in Chrome's toolbar.
3. Open the suggested **Next** problem, or pick any problem from the map.

Similar problems are found by comparing what each problem asks you to do, not just its tags.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/popup-dark.png">
    <img alt="The LeetCode Map popup on Two Sum. It suggests Group Anagrams as the next problem and shows related problems in layers: easy, medium, the current problem, medium and hard." src="assets/popup-light.png" width="460">
  </picture>
</p>

## What you can do

- **See related problems on a map**: easier problems on the left, harder on the right, laid out in layers by difficulty.
- **Get a next problem**: see the most similar problem you haven't solved, at most one level harder, and why it was picked. Skip for another.
- **Check how similar a problem is**: click a node to see its difficulty, its similarity score and the topics it shares with your problem.
- **Filter**: show Easy, Medium or Hard, or unsolved problems only.
- **Track progress**: problems you've solved on LeetCode are marked automatically when you're signed in, or mark them yourself (right-click a node works too).
- **Switch to a list**: the same problems as a list you can scan.
- **Search**: jump to any of the 3,900+ problems by number or title.
- **Work offline**: your 20 most recent maps open without a connection.
- **Light or dark**: paper and slate themes that follow your system setting.

## Get help

**Found a bug?** [Open a bug report](https://github.com/shashankswe2020-ux/leetcode-map-support/issues/new?template=bug_report.yml). The form asks for the problem you were on and what happened, which is usually all I need to reproduce it.

**Have an idea?** [Suggest a feature](https://github.com/shashankswe2020-ux/leetcode-map-support/issues/new?template=feature_request.yml), or add a 👍 to an [existing request](https://github.com/shashankswe2020-ux/leetcode-map-support/issues?q=is%3Aissue+label%3Aenhancement) so I know what matters most.

**Prefer email?** Write to [shashank.swe.2020@gmail.com](mailto:shashank.swe.2020@gmail.com).

## Questions

<details>
<summary><b>Does LeetCode Map collect my data?</b></summary>
<br>
No. You don't need an account. Your solved problems, including any synced from LeetCode, are stored only in your own browser and never sent to LeetCode Map's server. To draw a map, the extension asks its server for the problems related to the one you're viewing. Read the full <a href="https://gist.github.com/shashankswe2020-ux/00599fca1a28a0aa4af5f52600f847d9">privacy policy</a>.
</details>

<details>
<summary><b>How does solved-problem sync work?</b></summary>
<br>
When you open the popup on a LeetCode problem while signed in, it asks LeetCode, through that tab, which of the problems on your map you've solved, and marks them. Problems you've marked yourself are kept. If you're signed out, manual marks work as before.
</details>

<details>
<summary><b>Which sites does it work on?</b></summary>
<br>
Problem pages on leetcode.com (<code>leetcode.com/problems/…</code>). On any other page, you can still search for a problem from the popup.
</details>

<details>
<summary><b>How are problems matched?</b></summary>
<br>
Each problem's description is compared with every other problem's, so two problems can match even when LeetCode tags them differently. The map shows the closest matches, and the score on each one tells you how close it is.
</details>

<details>
<summary><b>Why doesn't the map show every problem in a topic?</b></summary>
<br>
It shows the problems closest to the one you're on, not everything with the same tag. Busy maps show up to six problems per column; switch to List to see every related problem.
</details>

<details>
<summary><b>How up to date is the problem list?</b></summary>
<br>
The popup's footer shows when the dataset was last updated. New LeetCode problems appear after the next update.
</details>

---

<p align="center">
  Made by <a href="https://github.com/shashankswe2020-ux">Shashank</a>. If LeetCode Map helps you practise, you can <a href="https://buymeacoffee.com/shashanksw9">support the project</a>.<br>
  <a href="https://gist.github.com/shashankswe2020-ux/00599fca1a28a0aa4af5f52600f847d9">Privacy policy</a>
</p>
