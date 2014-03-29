Wrapper around github.com/kr/goven to automatically import and update third
party dependencies by the use of `go list` tool.

dependencies

    go install github.com/philips/goven

install

    curl https://raw2.github.com/simonz05/gov/master/gov -o /usr/local/bin/gov

usage

    $ gov

pass `-update` flag to update imported packages as well

    $ gov -update
