# Adding a Publication

Please use the template provided below when adding a new publication. Fill in
all the information to the best of your ability. If you have a preprint, be sure
to update it once the publication has been accepted. If your publication has
been accepted into a journal (congrats!), be sure to check back once you have
the publication details, such as the volume, issue, and page numbers.



## Keys and File Names

Each publication must have a unique key following this pattern:
`YYYY_CONFSHORTNAME_PAPERSHORTNAME`


All files for your publication should use this key consistently, only varying by
the file extension. For example: `2016_eurovis_pathfinder.pdf`


However, if there are multiple files of the same extension type, then the
"secondary" type specified with an underscore, as in
`2016_eurovis_pathfinder_supplement.pdf`.


## Steps to Adding a Publication

1. Add a `*.md` file in this folder following [this template](2016_eurovis_pathfinder.md).
2. Add a thumbnail **_and_** a larger teaser figure to the [assets/images/papers](../assets/images/papers] folder. [Read more about adding images here](../assets/images/README.md).
3. Upload you publication video (if you have one) and your preview video to YouTube and create an entry in the [videos folder](../_videos) folder.
4. Upload the following files to `/usr/sci/www/vdl/papers`:
    - publication PDF (`KEY.pdf`) - *mandatory*
    - thumbnail figure (`KEY.png`) - *mandatory*
    - bibtex file (`KEY.bib`) - *mandatory*
    - Supplementary Material PDF (`KEY_supplement.pdf`)
    - full video (`KEY.mp4`)
    - preview video (`KEY_preview.mp4`)



## Syncing with the SCI Server

Here is a sync script that you can run to sync a local folder with the SCI server.

``` bash
rsync * alex@shell.sci.utah.edu:/usr/sci/www/vdl/papers --protocol=29 -r
```
