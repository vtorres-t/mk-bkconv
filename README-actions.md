# Automation in this fork

This fork of mk-bkconv contains GitHub Actions that:

1. Automatically sync this fork with the original repository
   (galpt/mk-bkconv) every 12 hours.

2. Automatically build binaries for many operating systems and CPU
   architectures using GoReleaser.

3. Automatically publish the built files to GitHub Releases when a
   commit is made to the original repository.

No changes are pushed to the original repository.
Everything runs only inside this fork.