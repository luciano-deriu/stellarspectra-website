
## Run site in nginx on Docker

### Windows
> docker run --rm --name stellarspectra -p 80:80 -v C:\Development\repos\stellarspectra-website:/usr/share/nginx/html:ro nginx

### Mac
> docker run --rm --name stellarspectra -p 80:80 -v $(pwd):/usr/share/nginx/html:ro nginx

## Open in browser
> http://localhost/index.html

----

Credits:

	website template:
		html5up.net
		aj@lkn.io | @ajlkn

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Scrollex (github.com/ajlkn/jquery.scrollex)
		Responsive Tools (github.com/ajlkn/responsive-tools)