# Release process

1. Confirm that the changes intended for the release have been merged.
2. Review the changelog and proposed Release notes.
3. Choose a version according to [the versioning policy](VERSIONING.md).
4. Create and push a Git tag, for example `v1.0.0`.
5. Create a GitHub Release for that tag.
6. Review the generated notes and edit them for accuracy and clarity.
7. Attach release assets only when the project has actual distributable files.
8. Publish only when the contents and tag are correct.

`.github/release.yml` configures generated note categories.
`.github/RELEASE_TEMPLATE.md` is a manual copy-and-paste starting point; GitHub does not
automatically load it as a native Release template.
