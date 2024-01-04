# Anki and STEP Resources

Tip: The `README.md` file
[table of contents](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes#auto-generated-table-of-contents-for-readme-files)
can be viewed by selecting the hamburger menu on the same line as the title in
the viewer!

## About

This repository contains:

- CSVs of timings and titles for STEP 1 external resource videos
    - [Boards and Beyond (BNB) Google Sheet](https://docs.google.com/spreadsheets/d/1Wm41IYA7ty8o-c8en73YcsnBitMoIJBqOoivP46xPag/edit?usp=sharing)
    - [Pathoma Google Sheet](https://docs.google.com/spreadsheets/d/1NAeezYHHN5qXgC7AmfHF6CiWdOFn3YAh7ixa56eD64c/edit?usp=sharing)
    - [Physeo Google Sheet](https://docs.google.com/spreadsheets/d/1L3SIvoQ6W02KJylnQfod6kAduBXP7W1em84sDAmyLMA/edit?usp=sharing)
    - [Pixorize Google Sheet](https://docs.google.com/spreadsheets/d/1v8s2e8QmMmoTEHZEQ_TXM_1lj2-glj6Po8s870OZbZw/edit?usp=sharing)
    - [Sketchy Google Sheet](https://docs.google.com/spreadsheets/d/1tPFMKQ6lCDuS8vgn8HTWKh3omDXrUHzCvmoFzogr2CQ/edit?usp=sharing)
        - TODO: Add Biochem (if you know the full timestamps, please share!)
    - [Folder with above Google Sheets](https://drive.google.com/drive/folders/1rLeHmQgOzyJmIGUuPnUD3wDfIynowgbF?usp=drive_link)
- CSV of tags for AnKing v11

| Resource          | Total Runtime (h:mm:ss) |
| :---------------- | :---------------------: |
| Boards and Beyond | 120:31:46 |
| Pathoma           | 34:32:01 |
| Physeo            | 144:02:29 |
| Pixorize          | 109:08:39 |
| Sketchy Micro     | 13:39:45 |
| Sketchy Path      | 47:40:33 |
| Sketchy Pharm     | 27:09:37 |
| **Total**         | **496:44:50** |

## Suggested Tag Use

- Use a resource, then add the cards with a tag from that resources to a
filtered deck
    - `Tools → Create Filtered Deck`
    - Enter your criteria under the `Filtered Search`.
    Using a `*` at the end is advised. By default, searches use `OR` when
    multiple criteria are entered, but other operators can be specified.
    ```python
    # Grabs all the cards for the Sketchy Micro
    "tag:#AK_Step1_v11::#SketchyMicro*"

    # Grabs all the Bacteria cards for Sketchy Micro
    "tag:#AK_Step1_v11::#SketchyMicro::01_Bacteria*"

    # Grabs all the Gram Positive Cocci cards for Sketchy Micro Bacteria
    "tag:#AK_Step1_v11::#SketchyMicro::01_Bacteria::01_Gram_(+)_Cocci*"

    # Grabs all the cards for the Sketchy Micro Staph Aureus video
    "#AK_Step1_v11::#SketchyMicro::01_Bacteria::01_Gram_(+)_Cocci::01_Staph_aureus*"

    # Grabs all the Bacteria and Fungi cards for Sketchy Micro
    "tag:#AK_Step1_v11::#SketchyMicro::01_Bacteria*" OR "#AK_Step1_v11::#SketchyMicro::02_Fungi*"
    ```

## Tips

- Search `"-&gt;"` to find instances of `->` in cards
- Symbols that may be of use: → α β
- Turn off the exclamation mark timer in the AnKing deck
    - `Browse` → select any card → `Cards` (should open a new window) → `Styling`
    - Modify this code:
    ```css
    /* TIMER ON/OFF */
    .timer {
      display: block; /* ‘none’ or ‘block’ */
    }
    ```
    to this
    ```css
    /* TIMER ON/OFF */
    .timer {
      display: none; /* ‘none’ or ‘block’ */
    }
    ```
    and `Save`!

## Favorite Add-Ons

- [AMBOSS Official (Requires AMBOSS subscription)](https://ankiweb.net/shared/info/1044112126), Code: 1044112126
- [Basic Printing Support](https://ankiweb.net/shared/info/1025789669), Code: 1025789669
- [BetterSearch](https://ankiweb.net/shared/info/1052724801), Code: 1052724801
- [Colorful Tags (+ Hierarchical Tags)](https://ankiweb.net/shared/info/594329229), Code: 594329229
- [Custom Background Image and Gear Icon](https://ankiweb.net/shared/info/1210908941), Code: 1210908941
- [Image Occlusion Enhanced](https://ankiweb.net/shared/info/1374772155), Code: 1374772155
- [More Decks Stats and Time Left](https://ankiweb.net/shared/info/1556734708), Code: 1556734708
- [Progress Graphs and Stats for Learned and Matured Cards](https://ankiweb.net/shared/info/266436365), Code: 266436365
- [Rebuild All & Empty All for Anki 2.1](https://ankiweb.net/shared/info/1810938259), Code: 1810938259
- [Review Heatmap](https://ankiweb.net/shared/info/1771074083), Code: 1771074083
- [Special Fields](https://ankiweb.net/shared/info/1102281552), Code: 1102281552
- [Tag Data to CSV](https://ankiweb.net/shared/info/1656094334), Code: 1656094334

### Other Useful Add-Ons
- [Button Colours (Good, Again)](https://ankiweb.net/shared/info/2494384865), Code: 2494384865
- [Mini Format Pack](https://ankiweb.net/shared/info/295889520), Code: 295889520
- [Picmonic (no subscription required)](https://ankiweb.net/shared/info/40737180), Code: 40737180
- [UpToDate (Requires subscription; direct download)](https://www.wolterskluwer.com/en/solutions/uptodate/uptodate/anki-add-on#how-to)

## Additional Resources

- [Using the 8BitDo SN30 Pro Remote with ANKI](https://gist.github.com/emleddin/2854b6f33417d2823738caef0ef6c129)
- [Using the 8BitDo Zero 2 Remote with ANKI](https://gist.github.com/emleddin/d25eb8493e16a7e262d156e7c8f53e77)
- [UWorldToAnki Chrome Extension](https://chrome.google.com/webstore/detail/uworld2anki/phmlchhmidolklmhbieicjmeamkjfdif)

### Reddit Threads

- [2023: I matched every B&B video with a string of UWorld Question ID numbers on the same subjects ](https://www.reddit.com/r/medicalschool/comments/16dpri3/i_matched_every_bb_video_with_a_string_of_uworld/)
- [2023: Updated Sketchy Pharm/Micro Checklist](https://www.reddit.com/r/comlex/comments/14i1udg/updated_sketchy_pharmmicro_checklist/)
- [2022: Complete Notion Checklist for Bnb, Pathoma, Sketchy Micro, Pharma with corresponding Anki cards based on Anking V11](https://www.reddit.com/r/medicalschoolanki/comments/vucu2q/complete_notion_checklist_for_bnb_pathoma_sketchy/)
- [2022: UFAPS Checklist w/ Runtimes](https://www.reddit.com/r/step1/comments/u2e19p/ufaps_checklist_w_runtimes/)
- [2021: Boards and Beyond 2020 Compressed Checklist (corrected)](https://www.reddit.com/r/step1/comments/ld84m3/boards_and_beyond_2020_compressed_checklist/)
- [2021: Color-Coded STEP1 Excel Checklist](https://www.reddit.com/r/step1/comments/re7sly/finally_an_excel_checklist_with_all_of_the_usmle/)
- [2020: STEP2 Checklist for Sketchy Videos (All subjects)](https://www.reddit.com/r/Step2/comments/kcs15j/made_a_checklist_for_sketchy_videos_all_subjects/)
- [2020: Workflow spreadsheets for Boards & Beyond, Pathoma, and Sketchy Pharm/Micro](https://www.reddit.com/r/medicalschoolanki/comments/g4y58p/workflow_spreadsheet_with_boards_and_beyond/)
- [2020: Step 1 Resource Checklist Spreadsheet](https://www.reddit.com/r/step1/comments/g99b0y/step_1_resource_checklist_spreadsheet_pixorize/)
- [2019: Lists of all videos for Pathoma, Boards & Beyond, Sketchy Pharm, and Physeo](https://www.reddit.com/r/step1/comments/b48r6m/lists_of_all_videos_with_runtimes_in_pathoma/)
- [2017: Printable Pathoma and Sketchy Pharm To Do lists](https://www.reddit.com/r/medicalschool/comments/76coin/pathoma_and_sketchy_pharm_to_do_lists_printables/)
