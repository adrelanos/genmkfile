Comprehensive tests for genmkfile -- target-dispatch regression tests -- are
too high-volume for human review and live in the AI-maintained dist-ai repo,
not here:

  https://github.com/org-ai-assisted/dist-ai -> usr/share/genmkfile-tests/

Run them against this checkout:

    GENMKFILE_BIN="$PWD/usr/bin/genmkfile" genmkfile-tests
