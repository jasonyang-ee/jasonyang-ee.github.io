# Documentation Main User Site

[https://doc.jasony.org](https://doc.jasony.org)

Jason Yang's Main Documentation Site

This page is generated using mdBook.

## Mechanism

### User Site:

If you create a repository with the special name “{username}.github.io”, then GitHub Pages will generate a root website for your account as http://{username}.github.io.

### Project Site:

Later, if you create a repository called {projectname}, then GitHub Pages will generate a website by appending {projectname} at end of your user site as http://{username}.github.io/{projectname}.

### Custom Domain:

You can apply custom domain to the user site. Then, this effect will propagate to all project sites.

> http://customdomain.com

> http://customdomain.com/{projectname}


## Book Generation Locally:
* [Install Rust](https://www.rust-lang.org/tools/install)
* Install mdBook
	```bash
	cargo install mdbook
	```
* Build Book
	```bash
	mdbook build
	```
* Serve Book
	```bash
	mdbook serve
	```