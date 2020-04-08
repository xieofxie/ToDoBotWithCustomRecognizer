# LU

# Main

## Add
## Del
## Show
## Mark
## Cancel
## Help
## Greeting
Could be removed as it is part of chitchat

# Show
## Input List

## Next
## Previous

## Add
## Del
## Show

# Variable
conversation.listType: for interruption from show to del
conversation.page: for interruption from show to del
- remember to clear
- pay attention to order

taskContent

settings.displaySize

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

also for folder name <-> id mapping

# Flow

Since we can't circular call dialogs like:
    mark -> show(which to mark) -> mark(after selection) -> show(finish mark)

The first show should be within mark
