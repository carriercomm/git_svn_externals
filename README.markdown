git svn externals
======

Introduction
----------

This script can be used to clone an SVN repository with externals.

Usage
----------

1. Run 'perl git_svn_externals.pl' in the root of git-svn cloned repository
2. profit :)

Features
----------

1. Script fetches all svn externals specified recursively.
2. On subseqent runs script fetches new externals and updates existing ones.
3. Svn externals with revision specified will be updated to apropriate
   revisions everytime the revision specified changes in svn repository.
4. Running 'git svn dcommit' is possible due to all fetched svn externals
   being excluded from the "root" git repository.

Known problems
----------

None known.

Author
----------

Dmitry Sushko <Dmitry.Sushko@yahoo.com>
