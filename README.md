## Shakespeare Insult CLI Tool
This is a Node CLI tool for generating Shakespearean insults. Each insult has the shape verb/adjective adverb adjective noun, e.g. fawning greatly shard-borne pignut

#### Reference Materials
- [Rebase vs Merge](https://hackernoon.com/git-merge-vs-rebase-whats-the-diff-76413c117333)
- [conflict resolution](https://githowto.com/resolving_conflicts)
- [notes on the Git CLI](https://gist.github.com/Nathan-Schwartz/01f0cbe97e6b27a189f68271c2df5f6e)
- [git aliases](https://github.com/AriLFrankel/dotfiles/blob/master/git/.gitconfig#L3)

#### Getting started
- Fork and clone this repo
- Make sure it behaves well
- Consider adding a *remote* for upstream

#### O no! It's broken
- No problem! A hotfix came out!
- pull down the hotfix branch using *git fetch*
- Use git *cherry-pick* to selectively apply the fix commit from the hotfix branch

#### Let's review an incoming feature
- Use a *git worktree* to review the feature branch without disrupting your workflow

#### Now let's add a feature
- add a fun feature or just extend existing ones
- play with *patch add/reset*, *diff*
- If it's multiple commits, keep a clean history with *interactive rebase* and *squash/fixup*
- *resolve conflicts* with upstream
