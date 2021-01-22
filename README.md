# Dataview (Obsidian Plugin)

Like Notion Databases, but better. Provides several advanced views for viewing pages, objects, and other data in your vault.

## Roadmap

- [ ] **Better Queries**:
    - [ ] Select file title
    - [ ] Select creation time & last modify time
    - [ ] Select file length (in words, in bytes, etc).
    - [ ] Select from CSV (data is selected from CSV)
- [ ] **Query Filtering**:
    - [ ] Inferred data schema
        - [ ] Number
        - [ ] String
        - [ ] Date
        - [ ] Tag
        - [ ] Link
    - [ ] Simple '>', '<', '=' on numeric/string fields
    - [ ] 'Around' for date and numeric fields
    - [ ] 'today', 'next week', other date constants
- [.] **Views**:
    - [X] List View (a list with metadata)
    - [ ] Task View (collects tasks from entire vault)
        - [x] Collect tasks from whole vault
        - [ ] Check a task box and have it be checked in original file
    - [ ] Object View (create custom objects anywhere in a file & collect them into a list)
    - [ ] Calendar-based View (computed off of a date object, could be used for dailies)
    - [ ] Timeline View
    - [ ] Gallery View (primarily for images)
    - [ ] Heirarchical View (where some way of determining parent/child relationship is provided)
    - [ ] Embedded Graph View (?)
- [ ] **Better Views**:
    - [ ] Sort By
    - [ ] Show Hidden Properties
    - [ ] Live Updating View (when a new query match shows up)
    - [ ] Modal for auto-generating view codeblocks
- [ ] **Usability**:
    - [ ] Schema validation for objects (using a central `Schema.md` file probably)
