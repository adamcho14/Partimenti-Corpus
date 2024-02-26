# Partimenti-Corpus

Each source of partimenti has its folder (like: ```Fenaroli_Book_2```).
Within this folder, each partimento has its subfolder (like: ```Fenaroli 2-2```).
Within the partimento folder are the different representations of the partimento:

- An edition of the partimento itself -- bass line and numbers, as a MuseScore file (MuseScore: ```bass.mscz```)
- Export of the bass line MIDI: ```bass.mid```
- The bass line can be exported into further formats: MusicXML, MEI, etc.
- Subfolders with realizations: ```manual-composed```, ```manual-keyboard```, ```coconet```, ```anticipatory-transformer```, ```polyffusion```, etc.
- Within each subfolder, the MIDI of individual realizations done by the given method.
  Because there can be multiple realizations by each method, they should be numbered (already the first one):
  ```realization_1.mid```.

Manual realizations should contain some more information.
- For each manually composed realization, also a MuseScore file should be present (as well as other export formats).
- The file name should also contain some ID of who was doing the realization: ```realization_person1_1.mid```
- A separate table that contains more information about who is ```person1```, ```person2```, etc. exists,
  but is not necessarily shared with the repository yet -- only an anonymized version. This will be
  in the root directory as ```persons.json```.
