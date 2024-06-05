# Contributing

So, you want to contribute? Great!  
Contributing is not only about creating fixes, but also reporting bugs. Before reporting a bug, please make sure to use the latest core and database revision.  

Creating Pull Requests:
=======================

1. Fork it.
2. Create a branch (`git checkout -b fixes`) (Note: fixes is an arbitrary name, choose whatever you want here)
3. Commit your changes (`git commit -am "Added Snarkdown"`)
4. Push to the branch (`git push origin fixes`)
5. Open a Pull Request

We suggest that you create one branch for each C++ based fix: this will allow you to create more fixes without having to wait for your pull request to be merged.  
For the SQL files coming with C++ based fixes the naming schema is `YYYY_MM_DD_i_database.sql`, where `YYYY_MM_DD` is the date of the fix, `i_database` is the *ith* sql created that day for `database`.  
When doing changes to `auth` or `characters` database remember to update the base files (`/sql/base/*`).  
For SQL only fixes, please [create a ticket](https://github.com/ThunderCoreWoW/ThunderCore3.3.5/issues/new/choose).
Since it's very unlikely that your Pull Request will be merged on the day that you open it, please name the files with an impossible date to avoid merging issues ie: 2015_13_32_00_world.sql

Requirements
============

Software requirements are available in the Github project for
Windows, Linux and Mac OSX.

If you choose Linux, we recommend to use Debian 8, since it's the Linux that we use to test compilations.
