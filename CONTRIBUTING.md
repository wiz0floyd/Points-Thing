# Contributing

## General requirements

- Pull request descriptions must be explicit and descriptive to what is being changed.
  - Changes that are not within the scope of the description will result in the entire PR being rejected
- No updates should be made directly to the automatically generated ServiceNow folders. Updates to these files should be done via the [Regular method](README.md#manually) described on the readme.
- Low effort/spam Pull Requests will be marked as spam accordingly.
- Filenames should not have special characters that are not allowed on normal file systems (eg. do not put ! in the file name).

## Messages are enough!

Along with new features, or working on any issues that appear in this repo's issues tab, we welcome you to simply submit a new message too!

1. Go to the `x_snc_points_thing_messages` table on your instance.
2. Submit a new message.
3. Return to the list view. 
4. Check the checkbox next to the message record you added in the message list.
5. Right click on the list header and choose "Create Application Files."
6. Choose **New install and upgrades** and select OK
7. Via Studio, commit your changes and open a new Pull Request!