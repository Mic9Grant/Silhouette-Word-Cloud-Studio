# Data handling

The reviewed code processes entered text, images and imported fonts in browser memory. It contains no application backend, analytics script, or explicit text/image upload request. Google Fonts requests contact external font services. In a compatible host, saving may use that host's download integration; otherwise it uses a browser download.

The code has no persistent project-save facility. Download artwork before closing or refreshing the page. Hosting providers and browser extensions may have their own data handling beyond this application's code.
