# [Twitter Bootstrap](http://twitter.github.com/bootstrap/) skeleton for [DocPad](https://github.com/bevry/docpad)
Simple and flexible HTML, CSS, and Javascript for popular user interface components and interactions.

Note: The docpad-less compiler breaks when using the `@import` directive - to change Bootstrap's LESS, you need to compile manually.

## Getting Started

1. [Install DocPad](https://github.com/bevry/docpad)

1. Install the LESS compiler (if you want to change Bootstrap's LESS)
	``` bash
	npm install -g less jshint recess uglify-js
	```

1. Clone the project and run the server

	``` bash
	git clone git://github.com/docpad/twitter-bootstrap.docpad.git
	cd twitter-bootstrap.docpad
	npm install
	docpad run
	```

1. [Open http://localhost:9778/](http://localhost:9778/)

1. Start hacking away by modifying the `src` directory

1. To re-compile bootstrap's LESS, run from the root directory:

	```bash
	lessc src/style/style.less src/files/style.css^C
	```


## License

This skeleton is made ["public domain"](http://en.wikipedia.org/wiki/Public_domain) using the [Creative Commons Zero](http://creativecommons.org/publicdomain/zero/1.0/), as such before you publish your website you should place your desired license here and within the `LICENSE.md` file.

If you are wanting to open-source your website, we suggest using the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/) for content and the [MIT License](http://creativecommons.org/licenses/MIT/) for code. In which case you'd probably want to use the following as your license:

	Unless stated otherwise, all content is licensed under the [Creative Commons Attribution License](http://creativecommons.org/licenses/by/3.0/) and code licensed under the [MIT License](http://creativecommons.org/licenses/MIT/), © [Your Name](http://your.website)

If you are wanting to close-source your website, we'd suggest using the following:

	Copyright [Your Name](http://your.website). All rights reserved.

Other included things such as themes and libraries are likely already licensed by their own invidual licenses, so be sure to respect their licenses too.

Thanks, the DocPad team loves you.