Update NEWS:

    r!git log --pretty=format:'- \%s (\%an)' x.y.z-1..HEAD

Bump version number in doxyqml/doxyqml.py

Commit

Create tarball:

    python setup.py sdist --formats=bztar

If ok, create "x.y.z" tag:

    git tag -a x.y.z

Push:

    git push
    git push --tags

Update project page

Blog
