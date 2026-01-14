# prebuilt-synology-dnsmasq

For hacking about, I needed a simple cross-compile for dnsmasq -- this is that.

Perhaps I'll roll it into the use-case later, but for now, I need a reliable, repeatable build to
bisect the objective.

NB: Upstream -- http://thekelleys.org.uk/git/dnsmasq.git and https://thekelleys.org.uk/dnsmasq/doc.html --
indicate GPL2 or GPL3, so this repo is similarly GPL2 due to viral nature of the license.  Please
propagate that respect for Simon Kelley's request.

## Build

It should be simply:

0. you have bazelisk installed as "bazel" in your path.
1. bazel build //...
