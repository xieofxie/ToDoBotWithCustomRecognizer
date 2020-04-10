# LU

## Main Dialog
- Add
- Del
- Show
- Mark
- Cancel
- Help

## Show Dialog
- Input List
- Next
    - **note it will conflict with content of task**
- Previous
- Show ToDo

## Add Dialog
## Del Dialog
## Mark Dialog

# Variable
conversation.listType
- for interruption from show to del
- remember to clear
- pay attention to order

conversation.page
- for interruption from show to del

taskContent
containsAll

settings.displaySize
settings.interruptScore
settings.intentScore

url

turn.token
turn.listToId
- list name to id in outlook
- assume no deletion

{
    // Index
    Id,
    IsCompleted,
    Topic,
    id,
}

tasks
todos
- for display

# Flow

support number in mark
support all in first show in mark

# Interruption Test
**if prompt in show, interrupt will not go back**

help, cancel always included

## Add
### Ask list type
- add
- show
- mark

### Ask content
- add
- show
- mark

## Show
### Ask list type
- add
    - V
- show
    - not needed here
- mark
    - V

### Ask next/prev
- add
    - V
- show
    - V
- mark
    - V

## Mark
### Ask list type
- add
- show
- mark

### Ask content
- add
- show
- mark
