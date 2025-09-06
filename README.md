For sshimpanzee:
https://github.com/lexfo/sshimpanzee

Build of sshimpanzee is currently failing because submodule libwsclient points to https://github.com/payden/libwsclient.git, which doesn't seem to exist anymore (or is no longer public).

Google-fu found a clone/archive of the repo, looks like an outright merge of master branch of that repo into what is now Archives/payden_libwsclient.
You might ask, well why not just use current branch of that?  Looks like a bunch of crypto mining code was merged in, and most of the wsclient stuff was deleted.

Head/last commit of payden/libwsclient was d416fcb62c.  
https://code.garrettmills.dev/Archives/payden_libwsclient/src/commit/d416fcb62c2d49b956433b0ea9081802eee6c534

This repo, just going to mirror that historic last commit of that repo before it fell off the face of earth.
https://code.garrettmills.dev/Archives/payden_libwsclient/archive/d416fcb62c2d49b956433b0ea9081802eee6c534.zip

Renamed the original README.md to README.md.original, otherwise preserving pristine state of that codebase, that commit.
Now sshimpanzee/.git/.gitmodules can point HERE :) YW
