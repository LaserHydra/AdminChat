**Admin Chat** allows admins to write in an admin-only chatroom.

## How to talk in the admin chatroom
To talk in the admin chatroom, either prefix your message with the configured prefix (default: `@`),
or toggle admin chat with the `adminchat` command.

## Permissions
- **adminchat.use** -- required to use the admin chatroom

## Commands
When running commands in chat, make sure to prefix them with a slash '/'.
- **adminchat** -- used to switch from regular to admin chat and back

## Configuration
```json
{
  "Prefix (admin chat is used when message starts with this)": "@",
  "Format (how the message is formatted in chat)": "[#red]Admin Chat[/#] [#grey]{name}[/#]: {message}"
}
```

## Localization
```json
{
  "Enabled Admin Chat": "You are now talking in admin chat.",
  "Disabled Admin Chat": "You are no longer talking in admin chat."
}
```