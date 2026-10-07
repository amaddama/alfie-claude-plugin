---
name: find-a-time
description: Find when the user, an Alfie friend or a whole team is free. Use when the user asks "when am I free", "when can I meet X", "find time with the team", "is Jackie free Thursday", or wants options before booking.
---

# Find a time with Alfie

Pick the tool by who's involved:

| Who | Tool | What it uses |
|---|---|---|
| Just the user | `find_free_time` | the user's calendar, 9 AM–6 PM |
| The user and one Alfie friend | `check_friend_availability` | both calendars, at the level the friend chose to share |
| A team | `find_team_time` | every member's busy times (never event names) |

## Steps

1. Work out the range from the request: a single day ("Thursday"), or a span ("next week", "in the next two weeks"). Default to the next 5 working days when they don't say.
2. Pass the meeting length if they gave one; otherwise 30 minutes (60 for lunch, dinner or coffee).
3. For someone who isn't an Alfie friend, Alfie can't see their calendar. Use `find_free_time` for the user's side and say that the other person's availability isn't known. Offer to send them a friend request (see friends-and-teams) so next time Alfie can check both.
4. Offer **two or three** good options, not a long list. Prefer reasonable hours and avoid back-to-back slots when there's a choice.
5. When the user picks one, book it with the book-a-meeting skill.

## Good to know

- Alfie's cards let the user pick a time with a tap. Mention that rather than repeating every slot in text.
- A friend may share busy times only. Don't guess what their events are.
