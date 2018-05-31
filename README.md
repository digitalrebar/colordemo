# Color Demo Example

For Digital Rebar Provision

To install the colordemo content pack, use the following command:

  `drpcli contents bundle colordemo-v1.yaml`

To inject/install it to a Digital Rebar Provision endpoint, use:

  `drpcli contents create ./colordemo-v1.yaml`

If you make changes to the local files (updates, edits, fixes, etc), and 
want to update the already installed conent pack, rebundle the changes, 
then update as follows:

  `# edit files as desired`

  `drpcli contents bundle colordemo-v2.yaml`

  `drpcli contents update colordemo ./colordemo-v2.yaml`

## Feature in Videos!

* Creating Content: https://youtu.be/79Y-3IOguZk
* Bundling: https://youtu.be/JUyzFNkLyZU
