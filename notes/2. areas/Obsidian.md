Alice's PAANDA knowledge management system

Directories:
- `1. projects` - for specific project documentation, one folder per project
- `2. areas` - for more generic notes
- `3. archive` - for old projects
- `4. network` #contact - for people
- `5. daily` #daily - for daily notes
- `6. attachments`
- `9. templates`

## Plugins
- Backlinks
- Daily notes - use `YYYY/MM-MMMM/YYYY-MM-DD-dddd` as the format and use the Daily Note Template as the template
- Calendar
- Dataview
- Jira issue - configure your Jira server
- Pinboard Sync - optional but a nice addition if you use pinboard.in
- Templater - set the `9. templates` directory as the template source, set `person.md` as the template for the `4. network` directory

You'll need to configure each of these yourself

Sync is currently running on top of OneDrive (which is a company standard). For the most part this works just fine, with fewer problems than other methods I have tried.

## Unsolved problems

- Shared documentation belongs in Confluence, which isn't synced here
- This vault is used for work purposes, sometimes it would be useful to have some notes from my personal vault available here (I can't use a single Vault because this risks data leaks in either direction)
- Alice doesn't understand zettlekasten

## References

* Person template based on https://juliaferraioli.com/blog/2023/obsidian-rolodex/
* Daily template based on https://dannb.org/blog/2022/obsidian-daily-note-template/
* Structure based on PAAN but with added dailies and Areas probably used incorrectly (it should probably be Anything else) https://forum.obsidian.md/t/paan-starter-kit/21782 
* Decision template based on https://adr.github.io/madr/
