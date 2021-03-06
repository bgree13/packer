# Packer Website

This subdirectory contains the entire source for the [Packer Website][packer].
This is a [Middleman][middleman] project, which builds a static site from these
source files.

## Contributions Welcome!

If you find a typo or you feel like you can improve the HTML, CSS, or
JavaScript, we welcome contributions. Feel free to open issues or pull requests
like any normal GitHub project, and we'll merge it in.

## Running the Site Locally

1. Install [Docker](https://docs.docker.com/engine/installation/) if you have not already done so
2. Clone this repo and run `make website`

Then open up `http://localhost:4567`. Note that some URLs you may need to append
".html" to make them work (in the navigation).

[middleman]: https://www.middlemanapp.com
[packer]: https://www.packer.io
