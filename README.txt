Wrapper around github.com/kr/goven to automatically import and update third
party dependencies by the use of `go list` tool.

Creates a folder called `third_party` in which all external dependencies are
copied. Rewrites the import path for your source files. Rewrites import path for
third party packages if they depend on other third parties.

dependencies

    go install github.com/philips/goven

install

    curl https://raw2.github.com/simonz05/gov/master/gov -o /usr/local/bin/gov

usage

    gov <args> [options]


commands

    list        list dependencies
    up          update dependencies

options

    -a|--all    update all dependencies
    -h|--help   show help
