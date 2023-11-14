# Broom
A file system broom. Finds and re-organises duplicate files, folders and repositories scattered about your hard disks.

# Problem

I have hundreds of software packages, code projects, database files and text, photo, audio and movie content distributed around my internal systems going back 30 years. 

There are copies of USB stick data stuck into folders here and there which are copies of hard disk files from elsewhere. 

There are file systems on multiple machines with multiple operating system and in the cloud.

That represent a history of my uncoordinated activity. It's a mess. 

The complication is that some of them are git or mercurial repositories with or without working folders.

Which, as repositories, should be considered as a package not as folders and files as such, but how far the history got to. 

I know I have copies of the same repository in multiple places with different extents to the histories, some of which are potentially interleaved activities (shriek). 

I have versions of music (songs) which are broken (content has been corrupted) due to some weird system disk malfunction (cross linked files). 

I have files with appended file elements that are date/time stamps that some software added to discriminate actual copies.


My objective is to migrate a single valuable copy of my files into a unified and understandable structure- maintaining folder structures of repositories as far as possible under the new root. These can be used going forward, reducing storage use and helping me find stuff.

Consider it a stiff broom on a dusty ancient warehouse floor.

## What do I need to do.

* Reduce the workload that is pointless - Produce a list of folders to exclude from indexing which are system or application vendor folders.
* Establish the storage scope - local / network / cloud
* Design and create an index all of of the qualifying folders and files gathering attribute information for each object. Each object to have its lineage to the device root.
* Create a set of rules about how to handle devices folders and files.
* Create a set of rules about how to discriminate based on folder and file attributes.
* Create a set of reports for recommended actions based on rules and discriminators.
* Be able to run this on demand or as a scheduled job.
* Create a set up reports before action is taken.
* Create a list of actions to take on identified folders/files.

* Create ideal structure to map to
* Create rules
* Establish scope
* Run investigation
* Analyse information
* Determine recommended actions
* Implement actions

