---
title: Accounts
---

Engine accounts are authenticated using GitHub. If that doesn't work for your team and you need another login option to be able to use Engine, please write in to our <a onclick="Intercom('showNewMessage')">support</a> and let us know!

## Team collaboration

Engine accounts mirror your GitHub organizations. The first time you log in, we create a personal Engine account for you with the same name as your GitHub username.

The Engine GitHub application asks for permission to read which GitHub organizations you're in and their members and teams (but not code!). If you grant Engine permission to see an organization, we create an Engine account with the same name as that GitHub organization. All members of that organization on GitHub will be able to see the new account in Engine. This is how you create shared accounts in Engine and is how teams collaborate.

When you sign in to Engine, you will have access to each account owned by a GitHub organization that you're a member of. Use the organization account picker to switch accounts. If another member of a GitHub organization you belong to has already signed up the GitHub organization for Engine access, you’ll have access to that existing account.

If you’d like to work with additional team members and you are the admin of a GitHub organization, simply add them to your GitHub organization. If you aren’t an admin, have an admin add you to their GitHub organization.

## Adding an organization after signing up for Engine

If you're looking for a GitHub organization that you're a member of and don't see it in Engine, it's likely that Engine does not have read access for that organization.

If you want to Add or Remove an organization from Engine, you should manage those settings on GitHub. There, you will be able to <b>Grant</b> or <b>Revoke</b> access to Engine for organizations you can administer. For organizations you do not administer, you can <b>Request</b> access to Engine and the administrators will receive a request by E-mail.

If you're logged in to Engine, you can manage those settings on GitHub [here](https://engine-graphql.apollographql.com/github/manage). Changes to your GitHub settings will only be visible in Engine after logging out and back in or waiting up to 30 minutes.


## Why does Engine need access to my GitHub organizations?

GitHub’s OAuth service is used for read-only information about organizations and users. Engine won’t have access rights to your source code or to any other sensitive data.

Your team members are already part of the Github org, so if the Engine account is owned by that Github org then Engine knows who to allow access to the account for. As you add or remove team members from your Github org, Engine will know about that and accordingly update the authorization for those users.
