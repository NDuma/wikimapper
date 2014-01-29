## 0.6.0 (01-24-2014)
Features:
- Revamped, better-looking, more minimalistic interface
- Dynamic horizontal SVG sizing based on tree depth
- Enhanced interactive tree rendering for collapsing/expanding nodes and improved readability

Bugfixes:
- Fixed an issue where deleting the last tree in localStorage would cause errors and the welcome message to not appear as it should.

Github Issues Closed:
- #27, #30, #35, #45

## 0.5.2 (01-20-2014)
Features:
- Wikimapper now tracks pages visited on Wiktionary alongside Wikipedia.

Github Issues Closed:
- #40

## 0.5.1 (01-17-2014)
Bugfixes:
- Added "form_submit" to the transitionType filter for recording

Github Issues Closed:
- #44

## 0.5.0 (01-17-2014)

Features:
- Sessioning! Wikimapper can now handle concurrent wikipedia sessions, i.e., can manage and update multiple trees at once.
- Complete overhaul of event handling that is both much faster	AND much more reliable by no longer relying on a completely loaded DOM to inject a content script for data collection.
- Navigation transition events are filtered so that only 'links' and 'typed' events are recorded. This should discard page refresh, back button, reopened tab, and other similar noise events.

Bugfixes:
- Fixed dates sometimes displaying incorrectly in the history
- Recording a new root node no longer reset the entire tree

Github Issues Closed:
- #1 , #33 , #34 , #37 , #38 , #39 , #41 , #42