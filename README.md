# [Feedly OCRemix Scraper]()

Brainstorming mode:

* I subscribe to the [OCRemix latest mixes RSS feed]() in [Feedly]().
* I mark the tracks I would like to download on my computer later using the "Save for later" feature.
* I want to be able to:
	* Consume the list of "Saved for later" items from this feed specifically.
	* For each item, fetch the HTML target page.
	* Scrape the page for one of the mirror download links.
	* Initiate a download of the MP3 from a random mirror.

There are some underlying requirements:

* I will have to authenticate against feedly's api using my Google account in order to generate an OAuth authentication token.
* The above implies this project should exist as a web app loadable in a browser.
* While initiating downloads can be done from the command line using `curl`, it's probably more convenient for this to happen in the browser too.


## Requirements

* PHP v7.0+
<!--
	* intl
	* pdo + mysql
	* mbstring
	* mcrypt
	* memcached
	* openssl
 -->
* Apache v2.4+, nginx, who knows what else probably works.


## Installation

TBD


## Usage

TBD


## Contributing

### Code of Conduct

This project has adopted the [Contributor Covenant v1.4](http://contributor-covenant.org/version/1/4/) as its [code of conduct](CODE_OF_CONDUCT.md). All contributors are expected to adhere to this code. [Translations are available](http://contributor-covenant.org/).

### Reporting Issues

Please use [GitHub Isuses]() for listing any known defects or issues.

### Development

When developing this plugin, please fork and issue a PR for any new development.


## License

[MIT](LICENSE.md)


## Copyright

Copyright (c) 2016 Brian Porter
