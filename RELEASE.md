How to Prepare a New Release
============================

1. Update `$VERSION` in `efgallery` (near line 17).

2. Commit this change.

3. Tag this commit using git tag $VERSION.

4. Git push including tags: git push --tags

   Release zipfiles/tarballs will now be at

   - https://github.com/0-ast-0/efgallery/archive/$VERSION.zip
   - https://github.com/0-ast-0/efgallery/archive/$VERSION.tar.gz
