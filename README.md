## This is a tool that allows users to easily cross-post their Known posts to their Medium account.

Attention: this is designed to work with Known posts only, statuses, bookmarks etc. have not been tested.

Help:
> python knownToMedium.py -h

Make sure the medium folder is in the same folder as the knownToMedium.py file.

1. Insert URL of your Known posts
   * It should look something like https://yourdomain.com/content/posts/.
   * Copy the URL in knownToMedium.py (known_posts_url). Be careful to include the "/" at the end.

2. Insert Medium integration token
   * This token can only be used by your account and has no expiry date.
   * You can generate one at https://medium.com/me/settings.
   * Copy the generated token in knownToMedium.py (integration_token).

3. Insert Medium app credentials
   * From the Medium settings menu, go to 'Manage applications' and create a new app.
   * Copy the generated 'Client ID' code in knownToMedium.py (client_id).
   * Copy the generated 'Client Secret' code in knownToMedium.py (client_secret).

By default, Medium creates post drafts. You still have to manually confirm publication.

To directly publish the Medium post, use "-t public".

You're ready to go!


To do:

Create a storage file for the app credentials, site url and integration token.

