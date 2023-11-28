# Anki and STEP Resources

## About

This repository contains:

- CSVs of timings and titles for external resource videos
    - [Boards and Beyond (BNB) Google Sheet](https://docs.google.com/spreadsheets/d/1Wm41IYA7ty8o-c8en73YcsnBitMoIJBqOoivP46xPag/edit?usp=sharing)
        - TODO: Add Pathology
    - [Pathoma Google Sheet](https://docs.google.com/spreadsheets/d/1NAeezYHHN5qXgC7AmfHF6CiWdOFn3YAh7ixa56eD64c/edit?usp=sharing)
    - [Physeo Google Sheet](https://docs.google.com/spreadsheets/d/1L3SIvoQ6W02KJylnQfod6kAduBXP7W1em84sDAmyLMA/edit?usp=sharing)
    - [Pixorize Google Sheet](https://docs.google.com/spreadsheets/d/1v8s2e8QmMmoTEHZEQ_TXM_1lj2-glj6Po8s870OZbZw/edit?usp=sharing)
    - [Sketchy Google Sheet](https://docs.google.com/spreadsheets/d/1tPFMKQ6lCDuS8vgn8HTWKh3omDXrUHzCvmoFzogr2CQ/edit?usp=sharing)
        - TODO: Add Biochem
    - [Folder with above Google Sheets](https://drive.google.com/drive/folders/1rLeHmQgOzyJmIGUuPnUD3wDfIynowgbF?usp=drive_link)
- A list of tags for AnKing v11
    - TODO: FirstAid, Physeo, Pixorize, Step2
- Coming Soon: Escaped list of tags for AnKing v11

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

## Additional Resource

- [Using the 8BitDo Zero 2 Remote with ANKI](https://gist.github.com/emleddin/d25eb8493e16a7e262d156e7c8f53e77)

## Favorite Add-Ons

- [AMBOSS Official (Requires AMBOSS subscription)](https://ankiweb.net/shared/info/1044112126), Code: 1044112126
- [Basic Printing Support](https://ankiweb.net/shared/info/1025789669), Code: 1025789669
- [BetterSearch](https://ankiweb.net/shared/info/1052724801), Code: 1052724801
- [Colorful Tags (+ Hierarchical Tags)](https://ankiweb.net/shared/info/594329229), Code: 594329229
- [Image Occlusion Enhanced](https://ankiweb.net/shared/info/1374772155), Code: 1374772155
- [More Decks Stats and Time Left](https://ankiweb.net/shared/info/1556734708), Code: 1556734708
- [Progress Graphs and Stats for Learned and Matured Cards](https://ankiweb.net/shared/info/266436365), Code: 266436365
- [Rebuild All & Empty All for Anki 2.1](https://ankiweb.net/shared/info/1810938259), Code: 1810938259
- [Review Heatmap](https://ankiweb.net/shared/info/1771074083), Code: 1771074083
- [Special Fields](https://ankiweb.net/shared/info/1102281552), Code: 1102281552
- [Tag Data to CSV](https://ankiweb.net/shared/info/1656094334), Code: 1656094334
