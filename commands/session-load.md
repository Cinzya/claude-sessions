Upload the current session by:

1. Taking the $ARGUMENT and check if exists in '.claude/sessions/$ARGUMENT.md', if $ARGUMENT contains file extension '.md' then check without '.m'. If file doesn't exist, notify user and ask to pick from all the *.md files located from '.claude/sessions/'.
2. Update the `$ARGUMENTS`.md to `.claude/sessions/.current-session`

I've loaded the session [$ARGUMENT]. Can you help me continue where I left off?