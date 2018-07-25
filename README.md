# euterpe-landing
A landing page for my home server.

## Installation
To install it, just download the contents of this repository with the green "Clone or download" button up there^^, and put it in your server's public HTML directory. You'll need to already have a web server like Apache or Nginx installed.

Most Linux systems probably already have Apache installed. So, you can probably put these files in `/var/www/html` and it'll work. If the server isn't already running, you'll need to start it—the command for this is probably `sudo systemctl start httpd` or `sudo systemctl start apache2` or something (google it for your distro).

## Configuration
Just edit the `<body>` section of index.html to your liking -- it's pretty simple so it should be easy enough to figure out even if you don't know much about HTML.

Put any images in the images directory. Ideally you want to use 256x256 square images, but it should still look okay if they're a different size or not quite square.
