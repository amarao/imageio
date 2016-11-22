How to update package to new upstream version
---------------------------------------------

1. merge tag to branch 'debian'
2. Bump version (dch -i for debian/changelog). Use same version as tag

How to build
------------

1. Checkout 'debian' branch. Work dir should be clean (everything commited or removed).
2. Update debian/changelog - signature at the top entry should match available gpg key
3. Run gbp buildpackage
