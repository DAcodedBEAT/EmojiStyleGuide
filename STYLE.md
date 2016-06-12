## Git Commit Message

All Git Commit Messages **MUST** meet this Text Format:
```
:emoji1: (:optional_additional_emojis:) Subject
Message Body
(New Line)
```

### Rules
----
1. Message Subject **SHOULD** begin with _at least_ one emoji (see below for the [list of Suggested Emojis](#suggested-emojis)).
3. Total characters of the _Subject Line_ **MUST** be _Less Than or Equal_ to **72** chars long.
 - _NOTE_: preferred length of commit message's subject is under 50 characters
4. Use valid [MarkDown](https://help.github.com/articles/basic-writing-and-formatting-syntax/) format in _Message Body_.
5. All WIP (Work In Progress) commits **MUST** have the WIP Emoji (see [below](#suggested-emojis)).

### Notes
----
+ _IMPORTANT_: All **WIP** commits **should** be avoided!.
+ _NOTE_: Every raw emoji Text (`:emoji:`) is counted as one character!

---

### Suggested Emojis
-------------

| Emoji | Raw Emoji Code | Description |
|:---:|---|---|
| :hammer: | `:hammer:` | when improving the **format**/structure of the code |
| :rocket: | `:rocket:` | when improving **performance** |
| :books: | `:books:` | when writing **docs** |
| :bug: | `:bug:` | when fixing a **bug** |
| :fire: | `:fire:` | when denoting a **hotfix** |
| :x: | `:x:` | when **removing code** or files |
| :white_check_mark: | `:white_check_mark:` | when adding **tests** |
| :lock: | `:lock:` | when dealing with **security** |
| :arrow_up: | `:arrow_up:` | when upgrading **dependencies** |
| :arrow_down: | `:arrow_down:` | when downgrading **dependencies** |
| :art: | `:art:` | when improving **UI**/Cosmetic |
| :construction: | `:construction:` | **WIP** (Work In Progress) Commits |
| :gem: | `:gem:` | New **Release** |
| :tada: | `:tada:` | **Initial** Commit |
| :sparkles: | `:sparkles:` | when introducing **New** Features |
| :zap: | `:zap:` | when introducing **Backward-InCompatible** Features |
| :bulb: | `:bulb:` | New **Idea** |
| :wrench: | `:wrench:` | changing **Configuration** |


## Git Pull Request

All Git PRs  **MUST** meet this Text Format:

```
[<KANBAN_TICKET_NUM>] <SUMMARY>
<KANBAN_TICKET_LINK>
(any other information)
```


### Rules:
----
1. After initial PR creation, "Needs Review" label must be added.
2. Upon second comment denoting approval from code review, switch label to next step in kanban board.
