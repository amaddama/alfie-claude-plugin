---
name: friends-and-teams
description: Manage Alfie friends and teams. Use when the user wants to add a friend, connect with someone, see their friends, create a team, invite people to a team, set their default team, or delete a team.
---

# Friends and teams in Alfie

Friends and teams are how Alfie sees other people's availability, so it can find a time that works for everyone and book in one step.

## Friends

- **Add a friend:** `add_friend` with their email. They get an invitation and choose what to share (busy times only, or full details). Only send requests the user asked for, and each person has a limited number of invites per day.
- **See friends:** `list_friends` shows each friend and what they share.
- Once someone accepts, use `check_friend_availability` to find times with them.

## Teams

- **Create a team:** `add_team` with a name and the members' emails or names. The user becomes admin and members get an email invitation. Members' busy times become visible to the team once they join (never event names).
- **Invite more people:** `add_team_members` (team admins only).
- **See teams:** `list_teams`.
- **Default team:** `change_default_team` sets what "the team" means when the user has several.
- **Delete a team:** `cancel_team` (admins only). Confirm with the user first, naming the team. Calendars and friendships aren't affected.

On Google Workspace, coworkers in the same organization can be found without signing up. Anyone with a Google account can be invited to a team.

## Good to know

- Never add friends or invite people the user didn't name.
- If the user is new to Alfie, `get_started` shows what it can do with examples.
