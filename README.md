# Alfie for Claude

Book, move and cancel Google Calendar meetings by just saying who and when. No scheduling links.

Say "Meet Jackie for lunch on Friday at the Ferry Building" and Alfie finds Jackie's email, checks when you're both free if you're connected as friends, and sends a normal calendar invite with a Google Meet link. Nothing for the other person to fill out.

## What's included

- **The Alfie connector** at `https://helloalfie.ai/mcp`: Alfie's calendar, contacts, friends and teams tools. After installing, open the plugin's Connectors tab, select Connect, and sign in with Google.
- **Skills** that teach Claude how to use Alfie well:
  - `book-a-meeting`: book with people by name, with sensible defaults for length, title and place
  - `find-a-time`: find when you, an Alfie friend, or a whole team is free
  - `change-or-cancel`: move, edit or cancel a meeting, confirming before anything is cancelled
  - `my-schedule`: answer "what's on today?" and similar questions
  - `friends-and-teams`: add friends, create teams and set your default team

## What it connects to and what it sends

This plugin contains only Markdown and JSON. It runs no code on your computer. It connects Claude to one remote server, `https://helloalfie.ai/mcp`, operated by Moxi-Kaizen, which reads and changes your Google Calendar and reads your contacts after you sign in with Google. Invitations go to the guests you name. Nothing is sent anywhere else.

- Privacy policy: https://helloalfie.ai/privacy
- Terms: https://helloalfie.ai/terms
- Setup help: https://helloalfie.ai/connect
- Support: support@helloalfie.ai

## Requirements

A Google account with Google Calendar. Alfie works with Google Workspace and personal Gmail accounts.

## License

MIT, see [LICENSE](LICENSE).
