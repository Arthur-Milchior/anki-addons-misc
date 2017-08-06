# Add-on Descriptions

These are the add-on descriptions, as found on [AnkiWeb](https://ankiweb.net/shared/addons/).

------------------------------------------

### Table of Contents

<!-- MarkdownTOC -->

- [anki-browser-batch-edit.py: Batch Note Editing](#anki-browser-batch-editpy-batch-note-editing)
- [anki-browser-create-duplicate.py: Duplicate Selected Notes](#anki-browser-create-duplicatepy-duplicate-selected-notes)
- [anki-browser-create-filtered-deck.py: Create Filtered Deck from the Browser](#anki-browser-create-filtered-deckpy-create-filtered-deck-from-the-browser)
- [anki-browser-external-editor.py: External Note Editor for the Browser](#anki-browser-external-editorpy-external-note-editor-for-the-browser)
- [anki-browser-more-hotkeys.py](#anki-browser-more-hotkeyspy)
- [anki-browser-refresh.py: F5 to Refresh the Browser](#anki-browser-refreshpy-f5-to-refresh-the-browser)
- [anki-browser-replace-tag.py: Search and Replace Tags](#anki-browser-replace-tagpy-search-and-replace-tags)
- [anki-browser-search-hotkeys.py: Browser Search Hotkeys](#anki-browser-search-hotkeyspy-browser-search-hotkeys)
- [anki-browser-search-modifiers.py: Browser Search Modifiers](#anki-browser-search-modifierspy-browser-search-modifiers)
- [anki-editor-autocomplete-whitelist.py](#anki-editor-autocomplete-whitelistpy)
- [anki-editor-custom-css.py: Customize Editor Stylesheet](#anki-editor-custom-csspy-customize-editor-stylesheet)
- [anki-editor-custom-tagedit.py: Tag Entry Enhancements](#anki-editor-custom-tageditpy-tag-entry-enhancements)
- [anki-editor-field-history.py: Editor Field History](#anki-editor-field-historypy-editor-field-history)
- [anki-editor-field-navigation.py: Quick Field Navigation Add-on for Anki](#anki-editor-field-navigationpy-quick-field-navigation-add-on-for-anki)
- [anki-editor-indentation-formatter.py: Indent and Outdent Paragraphs](#anki-editor-indentation-formatterpy-indent-and-outdent-paragraphs)
- [anki-editor-random-list.py: Insert Randomized Lists](#anki-editor-random-listpy-insert-randomized-lists)
- [anki-editor-sync-cursor-position.py: Sync Cursor Between Fields and HTML Editor](#anki-editor-sync-cursor-positionpy-sync-cursor-between-fields-and-html-editor)
- [anki-editor-tag-hotkeys.py: Editor Tag Hotkeys Add-on for Anki](#anki-editor-tag-hotkeyspy-editor-tag-hotkeys-add-on-for-anki)
- [anki-overview-deck-switcher.py: Switch Between Decks on the Main Screen](#anki-overview-deck-switcherpy-switch-between-decks-on-the-main-screen)
- [anki-overview-deck-tooltip.py: Deck Overview Stats Tooltip](#anki-overview-deck-tooltippy-deck-overview-stats-tooltip)
- [anki-overview-refreshmedia.py: Refresh Media References](#anki-overview-refreshmediapy-refresh-media-references)
- [anki-reviewer-card-stats.py: Extended Card Stats During Review](#anki-reviewer-card-statspy-extended-card-stats-during-review)
- [anki-reviewer-browse-creation.py: Browse Card in its Creation Context](#anki-reviewer-browse-creationpy-browse-card-in-its-creation-context)
- [anki-reviewer-browse-today.py: Open 'Added Today' from Reviewer](#anki-reviewer-browse-todaypy-open-added-today-from-reviewer)
- [anki-reviewer-hide-toolbar.py: Hide Toolbar in Reviewer](#anki-reviewer-hide-toolbarpy-hide-toolbar-in-reviewer)
- [anki-reviewer-hint-hotkeys.py](#anki-reviewer-hint-hotkeyspy)
- [anki-reviewer-more-answer-buttons.py: More Answer Buttons for New Cards](#anki-reviewer-more-answer-buttonspy-more-answer-buttons-for-new-cards)
- [anki-reviewer-progress-bar.py: Progress Bar](#anki-reviewer-progress-barpy-progress-bar)
- [anki-reviewer-puppy-reinforcement.py: Puppy Reinforcement](#anki-reviewer-puppy-reinforcementpy-puppy-reinforcement)
- [anki-reviewer-track-unseen.py](#anki-reviewer-track-unseenpy)
- [anki-reviewer-visual-feedback.py](#anki-reviewer-visual-feedbackpy)
- [anki-sched-advanced-newcard-limits.py: Limit New Cards to Less Than One](#anki-sched-advanced-newcard-limitspy-limit-new-cards-to-less-than-one)
- [anki-sched-sibling-spacing-whitelist.py](#anki-sched-sibling-spacing-whitelistpy)
- [anki-stats-true-retention-extended.py: True Retention by Card Maturity](#anki-stats-true-retention-extendedpy-true-retention-by-card-maturity)
- [anki-web-contextsearch.py: Context Menu Search](#anki-web-contextsearchpy-context-menu-search)

<!-- /MarkdownTOC -->

------------------------------------------

### anki-browser-batch-edit.py: Batch Note Editing

****

**OVERVIEW**

Adds a new menu item to the card browser that allows you to:

- **batch-add** information/media to a specific field
- **batch-replace** the contents of a specific field

The changes will be applied to all selected notes that feature the selected field.

**DEMO**

Here's a quick demo video that showcases these features:

[![YouTube: Anki add-on demo: Batch Note Editing](https://i.ytimg.com/vi/iCZzcSnAeH4/mqdefault.jpg)](https://youtu.be/iCZzcSnAeH4)

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**OTHER REMARKS**

The add-on uses the first selected note to generate the field list you're presented with. So please make sure to select a note with the right fields.

**CHANGELOG**

2017-08-05 – Ability to insert text as HTML
2017-05-13 – Only insert line-breaks when necessary
2016-12-11 – Support for adding text before existing content (thanks to @luminousspice for the idea)
2016-12-08 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

All credit for the original idea goes to <a href="https://www.reddit.com/user/TryhardasaurusRex" rel="nofollow">/u/TryhardasaurusRex on Reddit</a> who commissioned this add-on.

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-browser-create-duplicate.py: Duplicate Selected Notes

This add-on supplements the **card browser** by adding a keyboard shortcut and **menu** entry for **creating duplicates of notes**.

**USAGE**

Pressing the **shortcut** (`Ctrl+Alt+C` by default) or clicking on the *Create Duplicate* entry in the Edit menu will find all notes belonging to the selected cards and duplicate them in place.

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**IMPORTANT NOTES**

- All cards generated by each note will be duplicated alongside the note
- All duplicated cards will end up in the deck of the first selected card
- The duplicated cards should look exactly like the originals
- Tags are preserved in the duplicated notes
- Review history is NOT duplicated to the new cards (they appear as new cards)
- The notes will be marked as duplicates (because they are!)

**CHANGES**

2017-08-07 – Refactored code
2016-04-30 – Duplications can now be undone via CTRL+Z (using Anki's default restoration points)

**CREDITS**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on is based on "[Create Copy of Selected Cards](https://ankiweb.net/shared/info/787914845)" by Kealan Hobelmann.

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.


------------------------------------------

### anki-browser-create-filtered-deck.py: Create Filtered Deck from the Browser

Adds a hotkey and menu item to the browser that launches a **filtered deck creation** dialog **based on the current search**.

Hotkey: `Ctrl+Shift+D`

The dialog will be placed above Anki's main window (this is a limitation of the deck creation dialog).

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**CHANGELOG**

2017-08-05 – Refactored code
2016-05-28 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.


------------------------------------------

### anki-browser-external-editor.py: External Note Editor for the Browser

Extends the card browser with a **shortcut** and menu action that **launches an external editor window** for the current note (`CTRL`+`ALT`+`E`).

Here's a quick video demonstration:

[![YouTube: Anki add-on: External Note Editor for the Card Browser](https://i.ytimg.com/vi/dEL8204lOq4/mqdefault.jpg)](https://youtu.be/dEL8204lOq4)

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-02-21 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.


------------------------------------------

### anki-browser-more-hotkeys.py

Unpublished.

Adds two additional hotkeys to the card browser, CTRL+R for rescheduling cards and CTRL+ALT+I for inverting the selection.

------------------------------------------

### anki-browser-refresh.py: F5 to Refresh the Browser

Adds a **hotkey** to the browser that **refreshes the current view**. Useful when you've added new cards and want to repeat an existing search. Note: cards are sorted by creation time when refreshing the view.

Hotkey: `F5`

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-08-05 – Ability to define custom sorting column by editing the source code
2016-05-27 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was extended with the kind support of a fellow Anki user.

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-browser-replace-tag.py: Search and Replace Tags

Adds a **"Replace Tag" dialog** to the card **browser** that prompts for a tag and its replacement and then replaces the tag in all selected notes.

Hotkey: `Ctrl+Alt+Shift+T`

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-08-05 – Some smaller improvements and bug fixes
2016-06-04 – Switch to title case for menu entries
2016-05-27 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-browser-search-hotkeys.py: Browser Search Hotkeys

Allows you to set up **hotkeys for searches** in the **browser**

**USAGE**

Hotkeys follow this scheme: Ctrl+S –> (Modifier) + Key. I.e.: hit Ctrl+S to start the key sequence, let go of Ctrl+S, then hit the key assigned to  your search, plus an optional modifier.

You can use keyboard modifiers to control whether to add a term to the  search, negate it, remove it, or do something else. This follows the same  logic as the default behaviour in Anki when clicking on a search term in the sidebar.

New hotkeys can be defined in the source file by editing the `search_shortcuts` dictionary. Make sure to follow the existing syntax.

For instance, line 2 in the default `search_shortcuts` dict assigns the search
'added 1' (cards added today) to 'T'. This defines the following key sequences
in the browser:

    Ctrl+S -> T             replace search field with 'added:1'
    Ctrl+S -> Ctrl+T        add 'added:1' to existing search
    Ctrl+S -> Alt+T:        replace search field with '-added:1'
    Ctrl+S -> Ctrl+Alt+T:   add '-added:1' to existing search
    Ctrl+S -> Shift+T:      add 'or added:1' to existing search

The following keys are assigned by default:

    'A': {'search': ''},            # All together now
    'T': {'search': 'added:1'},     # Today
    'V': {'search': 'rated:1'},     # Viewed
    'G': {'search': 'rated:1:1'},   # aGain today
    'F': {'search': 'card:1'},      # First
    'C': {'search': 'deck:current'},# Current
    'N': {'search': 'is:new'},      # New
    'L': {'search': 'is:learn'},    # Learn
    'R': {'search': 'is:review'},   # Review
    'D': {'search': 'is:due'},      # Due
    'S': {'search': 'is:suspended'},# Suspended
    'B': {'search': 'is:buried'},   # Buried
    'M': {'search': 'tag:marked'},  # Marked
    'E': {'search': 'tag:leech'},   # lEech

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**CHANGES**

2017-08-05 – Refactored code
2016-04-27 – Implemented hotkeys for more searches. Thanks to ankitest!

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-browser-search-modifiers.py: Browser Search Modifiers

**Checkbox toggles that modify how the browser search behaves**

Adds two checkboxes to the browser search form that, when toggled, modify searches in the following way:

**Deck** (Hotkey: Alt+D): Limit results to current deck
**Card** (Hotkey: Alt+C): Limit results to first card of each note

![screenshot](screenshots/anki-browser-search-modifiers.png)

Based on the following add-ons:

- "Limit searches to current deck" by Damien Elmes
   (https://github.com/dae/ankiplugins/blob/master/searchdeck.py)
- "Ignore accents in browser search" by Houssam Salem
   (https://github.com/hssm/anki-addons)

Original idea by Keven on the [Anki support forums](https://anki.tenderapp.com/discussions/ankidesktop/17918-add-on-or-anki-feature-suggestion-show-only-front-card-in-browser-checkbox).

Special thanks to ankitest for testing and improving this add-on.

**License**

*Copyright (c) 2016 [Glutanimate](https://github.com/Glutanimate)*

The code for this add-on is hosted in my [misc Anki add-ons repository](https://github.com/Glutanimate/anki-addons-misc).

Licensed under the [GNU GPL v3](http://www.gnu.de/documents/gpl-3.0.en.html).

------------------------------------------

### anki-editor-autocomplete-whitelist.py

**Overview**

This is a modified version of the [Editor Autocomplete add-on for Anki](https://github.com/sartak/anki-editor-autocomplete). Instead of checking against a blacklist of non-autocompleted fields this implementation of the add-on will only enable autocomplete on fields you specify.

Fields to enable autocomplete on can be specified by modifying the `AutocompleteFields` array at the beginning of the script, e.g.:

```python
AutocompleteFields = [ "sources", "additional-info" ]
```

This version of the add-on also includes a hotkey that saves you the trouble of clicking on the autocomplete suggestion. It's set to <kbd>Alt</kbd> + <kbd>Return</kbd> by default.

All credit for the original add-on goes to Shawn M Moore ([@sartak](https://github.com/sartak/)).


------------------------------------------

### anki-editor-custom-css.py: Customize Editor Stylesheet

Allows you to customize the **stylesheet** of the **Editor widget** in Anki.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**USAGE**

Create an `_editor.css` file in your media collection, add your custom CSS rules to it, and restart Anki. Use the css class `.field` to format all fields in the Editor widget. The addon can be switched on and off in the main window via Tools - "Custom Editor Styling" (hotkey Shift+E in the Deck View). After changing this setting, reopen all Browser and Add windows.

Compatibility with the addon [Night Mode](https://ankiweb.net/shared/info/1496166067) (Version 2017-03-06): By default this addon is disabled when the Night Mode is activated.

Compatibility with the addon [Power Format Pack](https://ankiweb.net/shared/info/162313389) (Version 2017-05-14 ): If you have set a background-color in the class `.field` in your `_editor.css`, this overrides the orange background color that PFP applies in [Markdown Mode](https://github.com/Neftas/supplementary-buttons-anki#using-markdown). If you would like to restore that color you can modify your `_editor.css` as follows:

```
/* applies to all fields that are not in markdown mode */
.field:not(.mdstyle){
    /* place your custom field background color here: */
    background-color: #F5F6CE ! important;
}

/* applies to all fields in markdown mode */
.mdstyle {
    /* The default color PFP uses is #FFEDD3 */
    background-color: #FFEDD3 ! important;
}
```

Compatibility with future versions of Night Mode and Power Format Pack is not guaranteed. No further updates of this addon are planned.

**CHANGELOG**

2017-08-04 – Initial release

**CREDITS AND LICENSE**

*Copyright © 2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was commissioned by a fellow Anki user. All credit for the original idea goes to them.

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-custom-tagedit.py: Tag Entry Enhancements

A number of enhancements meant to **improve keyboard navigation** in Anki's **tag entry** field:

- adds `Return/Enter` as a hotkey to apply the first suggested tag
- adds `Ctrl+Tab` as a hotkey to move through the list of suggestions
- disables initial suggestion box popup when entering the field
- allows using ↑/↓ to invoke the tag suggestion box

**CHANGELOG**

2017-04-11 – Smaller bug fixes
2017-01-15 – Tags completed via *Enter* now follow the suggestion's capitalization; automatically append space to quick-completed tags
2016-12-28 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-field-history.py: Editor Field History

Improves Anki's *Add Notes* dialog with the following features:

- hotkeys that **copy** over tags and field **values of the last note** in the same deck
- a **searchable history window** that provides a list of last used values for the current field

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**USAGE**

`Ctrl + Alt + H` (Win/Linux) or `Cmd + O` (macOS) – Invoke history window
`Alt+Z` – Copy over current field from last note
`Alt+Shift+Z` – Copy over a a number of user-defined fields (see below)
`Ctrl + Alt + Shift + Z` (Win/Linux) or `Cmd + Alt + Shift + Z` (macOS) – Copy over all fields

**CONFIGURATION**

You can edit the add-on's source code to modify the following:

`history_window_shortcut`: controls the hotkey for invoking the history window
`field_restore_shortcut`: controls "Restore current field hotkey"
`partial_restore_shortcut`: controls "Restore a number of user-defined fields" hotkey
`full_restore_shortcut`: controls "Restore all fields" hotkey
`partial_restore_fields`: list of fields that are restored by the `partial_restore_shortcut`. Needs to be formatted as a python list (e.g. `["field1", "field2", "field3"]`).

**CHANGELOG**

2017-05-25 – Change history window hotkey on macOS to avoid key conflicts (thanks to Rene)
2017-05-13 – Preserve chronological order of suggestions
2017-03-08 – Add full-text-search to history window, increase entries to 100, new hotkey on macOS
2017-03-11 – Ensure that the add-on can only be run in the Add Cards screen
2016-12-13 – Fixed a rare bug that caused empty notes to appear
2016-06-04 – Added history window to the add-on (invoked via Ctrl+Alt+H)
2016-05-27 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-field-navigation.py: Quick Field Navigation Add-on for Anki

Implements shortcuts that allow you to **navigate** through your **fields** in the card **editor**.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**USAGE**

The following shortcuts are provided:

`Ctrl` + `1-9`: Switch focus to field 1-9
`Ctrl` + `0`: Switch focus to last field
`Alt` + `Shift` + `F`: Switch focus back to note fields from tag field (to complement Anki's inbuilt Ctrl + Shift + T) hotkey to switch to the tags field)

Note: In their current implementation the hotkeys will not work when the tag suggestions drop-down box is active. I am [still looking for a fix for this](https://anki.tenderapp.com/discussions/add-ons/4725-dd-on-development-unable-to-switch-editor-focus-back-to-web-view-when-tags-completer-is-active).

**CHANGELOG**

2017-08-07 – Adjustments for hidden fields used by add-ons such as Image Occlusion Enhanced
2016-04-19 – Reworked the add-on from scratch to have a much leaner footprint
2015-09-04 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2015-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-indentation-formatter.py: Indent and Outdent Paragraphs

Introduces two new buttons to the editor toolbar that allow you to **change the indentation of the current paragraph**. This add-on uses `<p>` elements instead of the `<blockquote>`s found in add-ons such as the Power Format Pack which should result in a more readable HTML source code.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-08-05 – Config option that controls whether to use existing tags or not
2017-05-13 – Ability to indent arbitrary tags. More config options (check the source-code header for more information)

**CREDITS AND LICENSE**

*Copyright © 2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was commissioned by a fellow Anki user who would like to remain anonymous. All credit for the original idea goes to them.

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-random-list.py: Insert Randomized Lists

Allows you to insert **randomized lists** into your notes.

**DOCUMENTATION**

The add-on requires a custom note type to work properly. Please consult the [README](https://github.com/glutanimate/anki-addons-misc/blob/master/anki-editor-random-list/README.md) for more information on its set-up. The add-on's use is also detailed on that page.

The lists generated by this add-on should be compatible with Anki and AnkiDroid. I have not tested this with AnkiWeb or AnkiMobile.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-05-14 – Initial release

**CREDITS AND LICENSE**

*Copyright © 2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was commissioned by a fellow Anki user who would like to remain anonymous. All credit for the original idea goes to them.

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-sync-cursor-position.py: Sync Cursor Between Fields and HTML Editor

Preserves the cursor position when switching back and forth between the note editor and HTML editing window (`CTRL+SHIFT+X`). Also improves the readability of the HTML code by introducing new lines between specific tags (`div`, `p`, etc.).

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**INTER-ADD-ON COMPATIBILITY**

Some add-ons like the the [Power Format Pack](https://ankiweb.net/shared/info/162313389) overwrite the same functions as this add-on. This doesn't pose an issue as long as *Sync Cursor Position* is loaded last. In case of the Power Format Pack add-on, the fact that *Sync Cursor Position* starts with an "S" should ensure that the latter is loaded after the former, but for some reason that's not always the case. If you do end up experiencing compatibility issues like this, you could try renaming the add-on, e.g. by prepending it with a "z" or a special character like "#".

**CHANGELOG**

2017-05-13 – Increase default window size (the size can also be adjusted in the config section of the source code now). Various smaller bugfixes.

**CREDITS AND LICENSE**

*Copyright © 2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was commissioned by a fellow Anki user who would like to remain anonymous. All credit for the original idea goes to them.

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-editor-tag-hotkeys.py: Editor Tag Hotkeys Add-on for Anki

Allows you to define **hotkeys** that **toggle specific tags** in the note **editor**.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**USAGE**

-- *Adding a Tag Hotkey* --

Edit `anki-editor-tag.hotkeys.py` and modify the `tags` dictionary with your custom hotkey assignments, e.g.:

    tags = {
        "Alt+Shift+1": u"Anatomy",
        "Alt+Shift+2": u"Physiology"
    }

Supported keyboard modifiers are: `Alt`, `Shift`, `Ctrl`, `Meta` (on Mac: `Meta` ≙ Control, `Ctrl` ≙ Cmd). The exact syntax is explained in the comments next to the dictionary.

-- *Clearing Tags Field* --

This add-on also includes a hotkey that clears the tags field: <code>Alt</code> + <code>Shift</code> + <code>R</code>

-- *Defining a Unique Tag* --

Sometimes you might want to quickly toggle between several different tags. For this purpose I've implemented a configuration option called unique_tags. Any items added to this list will cause their respective hotkeys to delete all other instances of unique tags aside from the one currently being triggered. 

For instance, if you set up hotkeys for "tag1" and "tag2" and add these tags to `unique_tags`, hitting the hotkey for "tag1" will delete "tag2" from the tags list and vice-versa.

To add a unique tag, simply update the following excerpt in the script:

    unique_tags = ["tag1", "tag2"]

Please make sure to preserve the formatting and quoting while doing so!

**CHANGELOG**

2017-05-08 – Update license
2017-04-11 – Reworked add-on from the ground-up: much more intuitive key assignments, preparations for Anki 2.1
2016-02-18 – Add support for unique tags; Misc bug fixes and improvements
2015-12-25 – Add support for unicode in toggled tags (thanks to aleksejrs)
2015-11-06 – Toggling tags also works in the card browser now
2015-10-27 – Added a hotkey to clear the tags field
2015-10-27 – Initial release

**CREDITS AND LICENSE**

*Copyright © 2015-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-overview-deck-switcher.py: Switch Between Decks on the Main Screen

Adds the following hotkeys to Anki's main deck browser screen:

`Ctrl + Tab`: **Switch** to **next deck**
`Ctrl + Shift + Tab`: **Switch** to **previous deck**

These also work in the detailed view of each deck and in the reviewer.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CONFIGURATION**

By default the hotkeys will skip decks that don't have any cards that are due or new. Filtered decks and custom study sessions are also ignored. You can change this by editing the add-on and setting the variables defined in the USER CONFIGURATION section at the top.

**CHANGELOG**

2016-07-30 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-overview-deck-tooltip.py: Deck Overview Stats Tooltip

**Hover** over your **decks** to see an overview of **review stats** and other information on the deck.

**Screenshot**

![](https://raw.githubusercontent.com/Glutanimate/anki-addons-misc/master/screenshots/main_deck_tooltip.png)

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**LICENSE AND CREDITS**

*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-overview-refreshmedia.py: Refresh Media References

Adds an entry in the **Tools menu** that **clears the webview cache** (hotkey: `Ctrl+Alt+M`). This will effectively refresh all media files used by your cards and templates, allowing you to display changes to external files without having to restart Anki.

The add-on will also update the modification time of your media collection which will force an upload of any updated files on the next synchronization with AnkiWeb.

Note: Might lead to increased memory consumption if used excessively

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2017-01-29 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-card-stats.py: Extended Card Stats During Review

Provides a **'Card Info' panel** that can be toggled on and off **while reviewing cards**.

This add-on is based on [Card Info During Review](https://ankiweb.net/shared/info/2179254157) by Damien Elmes and [Reviewer Show Cardinfo](https://github.com/steveaw/anki_addons/blob/master/reviewer_show_cardinfo.py) by Steve AW. It extends Damien's add-on with a review log table similar to the one found in the Browser.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**USAGE**

The visibility of the panel can be controlled through the *Tools* menu or `SHIFT+C`.

**SCREENSHOT**

![](https://raw.githubusercontent.com/Glutanimate/anki-addons-misc/master/screenshots/anki-reviewer-card-stats.png)

**CREDITS AND LICENSE**

*Copyright (c) 2012 Damien Elmes*
*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-browse-creation.py: Browse Card in its Creation Context

Adds commands to the Reviewer "More" menu and a hotkey (*C*) to **open the browser** on the **selected card**. The browser is configured to sort based on **creation date**, and select the card. Enables the card to be viewed in its  "creation context" ie notes that were created before/after in the same deck.

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**LICENSE AND CREDITS**

*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-browse-today.py: Open 'Added Today' from Reviewer

Adds a **menu item** into the **History menu** of the *Add* notes dialog that **opens a Browser on the 'Added Today'** view with the cards ordered by their creation time.

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**CHANGELOG**

2017-08-05 – Add hotkey for menu entry
2016-04-04 – Initial release

**CREDITS AND LICENSE**

*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc1).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-hide-toolbar.py: Hide Toolbar in Reviewer

The aim of the addon is to **free up** some **vertical screen space** while **reviewing** cards.

This is a slightly modified re-upload of an add-on by [Steve AW](https://github.com/steveaw/anki_addons). Below follow excerpts of the original description: 

==========

**RATIONALE**

For me this is useful as I have many cards that contain diagrams which can be fairly large. In addition. modern wide screen displays seem to feel more cramped vertically than horizontally.

The toolbar is made visible again when viewing decks and the overview.

The commands that are usually found on the toolbar are added to a new main window "Toolbar" menu. Shortcut keys should continue to function.

==========

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2016-04-03: Use internationalization for toolbar items (thanks to comment below)

**LICENSE AND CREDITS**

*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

------------------------------------------

### anki-reviewer-hint-hotkeys.py

Unpublished.

Based on [Hint-peeking Keyboard Bindings](https://ankiweb.net/shared/info/2616209911) by Ben Lickly. Adds two hotkeys to the reviewer: 'H' to reveal hints one by one, 'G' to reveal all hints at once.

------------------------------------------

### anki-reviewer-more-answer-buttons.py: More Answer Buttons for New Cards

Adds **extra buttons** to the Reviewer **for new cards** and **cards in learning**.

This is a slightly modified re-upload of an add-on by [Steve AW](https://github.com/steveaw/anki_addons). Below follow excerpts of the original description: 

==========

**SCREENSHOT**

![screenshot](https://raw.githubusercontent.com/Glutanimate/anki-addons-misc/master/screenshots/addcards_more_newcard_buttons.png)

**DESCRIPTION**

Adds anywhere between 1 to 4 new buttons to the review window when reviewing a new card or cards that are in learning mode. The new buttons function like the existing "Easy" button, but in addition, they reschedule the card to a different interval, which is randomly assigned between a lower and upper limit that is preset by the user (see below).

By default 3 buttons are added, with intervals: "3-4d" , "5-7d" , "8-15d". This can be changed in the source code.

**USE CASE**

I wanted this addon because many of my new cards do not need to be "Learned" as I created and added them myself, typically an hour or so before my first review session. I often add around 100-200 new cards per day, all on a related topic, and this addon allows me to spread the next review of the new cards that don't need learning out in time.

**HOW IT WORKS**

This add-on functions as if you click the "Easy" button on a new card, and then go to the browser and reschedule the card. This means that, in contrast to rescheduling the card, using one of the new answer keys will actually add a new entry to the card review history.

**INTER-ADD-ON COMPATIBILITY**

This add-on is oncompatbile with any other add-ons that also overwrite the `Reviewer._answerButtons` function, i.e. add-ons that also modify the answer button area.

**CONFIGURATION**

Open the add-on in a text editor of your choice and find the `extra_buttons` section below the header. This is a list of dicts, where each item of the list (a dict) is the data for a new button. This can be edited to suit, but **there can not be more than 4 buttons**. Values:

- Description ... appears above the button
- Label ... the label of the button
- ShortCut ... the shortcut key for the button
- ReschedMin ... same as the lower number in the Browser's "Edit/Reschedule" command
- ReschedMax ... same as the higher number in the Browser's "Edit/Reschedule" command

==========

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**CHANGELOG**

2016-05-11: Made answer buttons work properly when card is in learning mode (thanks to Dmitry Mikheev)
2016-05-10: Extend answer buttons to cards in learning (thanks to Dmitry Mikheev)

**LICENSE AND CREDITS**

*Copyright (c) 2013 Steve AW*
*Copyright (c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)*

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-progress-bar.py: Progress Bar



------------------------------------------

### anki-reviewer-puppy-reinforcement.py: Puppy Reinforcement

Uses **intermittent reinforcement** with **cute puppies** to encourage card review streaks.

Based on [Show Cute Dogs](https://ankiweb.net/shared/info/1125592690) by Michael Bertolacci.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**DIFFERENCES FROM THE ORIGINAL**

- Uses tooltips instead of a separate window
- The puppies are spread intermittently through your reviews. By default they will appear around every 10 cards (some take longer than others). You can customize this by editing the add-on)
- Customizable encouragement messages that change based on the card tally
- Removed cats and other non-puppies

**OTHER NOTES**

- The add-on comes with around 50 puppies by default, but you can add more by placing additional images in the puppy_reinforcement folder next to the add-on
- the tooltip will appear slightly higher than tooltips in Anki usually do. This is to prevent overlapping with other tooltips (e.g. the ones produced by the answer confirmation add-on)

**CHANGELOG**

2016-11-18 – Initial release

**CREDITS AND LICENSE**

(c) 2015 [mbertolacci](https://github.com/mbertolacci)
(c) 2016-2017 [Glutanimate](https://github.com/Glutanimate)

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-reviewer-track-unseen.py

------------------------------------------

### anki-reviewer-visual-feedback.py

------------------------------------------

### anki-sched-advanced-newcard-limits.py: Limit New Cards to Less Than One

Allows you to restrict the **number of new cards** for specific decks to **less than one per day**.

**CONFIGURATION**

Please edit the configuration section at the top of the source code to define the card limits. The syntax for setting up limits for a specific deck is as follows:

    deck_limits = {
        u"My deck name": 3
    }

where "3" corresponds to one new card every three days.

These settings will only apply to decks that have their new card limit set to "1" within Anki, so please make sure to do so before using this add-on.

**COMPATIBILITY**

This add-on has only been tested with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is probably **not supported** at this point in time.

**SUPPORTED PLATFORMS**

Like all add-ons that modify scheduling this add-on will only work on the desktop releases.

**CREDITS AND LICENSE**

*Copyright © 2017 [Glutanimate](https://github.com/Glutanimate)*

This add-on was commissioned by a fellow Anki user who would like to remain anonymous. All credit for the original idea goes to them.

Licensed under the [GNU AGPL v3](https://www.gnu.org/licenses/agpl.html). The source code for this add-on is available on [GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-sched-sibling-spacing-whitelist.py

Unpublished.

Based on [Sibling Spacing](https://ankiweb.net/shared/info/2951410923) by Andreas Klauer. Modified to follow a whitelist approach when choosing which note types to enable on. Check the comments in the source file for more information.


------------------------------------------

### anki-stats-true-retention-extended.py: True Retention by Card Maturity

This is a slightly modified version of the [True Retention add-on](https://ankiweb.net/shared/info/613684242) by Strider that breaks the **retention statistics** up **by card maturity**:

![](https://raw.githubusercontent.com/Glutanimate/anki-addons-misc/master/screenshots/anki-stats-true-retention-extended.png)

In addition to this, the add-on also allows you to define a custom card maturity threshold (`MATURE_IVL` at the top of the source code). This is set to 21 days by default.

**CREDITS AND LICENSE**

*Copyright 2016 Strider*
*Copyright 2017 [Glutanimate](https://github.com/Glutanimate)*

All credit for the original True Retention add-on goes to Strider. This modified version is based on a [post on the Anki support forums](https://anki.tenderapp.com/discussions/add-ons/8986-true-retention-how-to-change-value-of-mature-cards-extracted-from-21-to-90-days) by peter19220.

I wasn't able to find any licensing information for the original add-on, but since it reuses parts of Anki's code I think it's fair to assume that it's licensed under the same license as Anki itself (GNU AGPLv3). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.

------------------------------------------

### anki-web-contextsearch.py: Context Menu Search

A simple Anki add-on that adds **context-menu entries** to **search** the card browser and various online search providers for selected words. The entries will appear both in the Reviewer and Card Editor.

**COMPATIBILITY**

This add-on only works with Anki's stable release branch (2.0.x ≥ 2.0.30). The 2.1 beta branch is **not supported** at this point in time.

**SEARCH PROVIDERS**

Currently supported are Google, Google Images, and Wikipedia. You can add new providers by editing the source code and modifying the *SEARCH_PROVIDERS* list. Just make sure to follow the syntax of the other entries.

**CHANGELOG**

2017-08-05 – Refactored code
2016-01-26 – Only create a submenu when needed
2017-01-17 – Rewrote add-on, added support for online search providers
2016-04-19 – double-quote phrases when searching

**CREDITS AND LICENSE**

*Copyright (c) 2015-2017 [Glutanimate](https://github.com/Glutanimate)*

Based on 'OSX Dictionary Lookup' by Eddie Blundell and 'Search Google Images' by Steve AW.

This add-on was formerly known as "Search Browser for Selected Words".

Licensed under the [GNU AGPL v3](http://www.gnu.de/documents/gpl-3.0.en.html). The code for this add-on is hosted [on GitHub](https://github.com/Glutanimate/anki-addons-misc).

**MORE RESOURCES**

A lot of my add-ons were commissioned by fellow Anki users. If you enjoy my work and would like to hire my services to work an add-on or new feature, please feel free to reach out to me at <em>ankiglutanimate [αt] gmail . com</em>.

New to add-ons and Anki in general? Make sure to check out my [![YouTube playbutton](https://raw.githubusercontent.com/glutanimate/logos/master/youtube/playbutton.png) YouTube channel](https://www.youtube.com/c/glutanimate) where I post weekly tutorials on Anki add-ons and related topics.
