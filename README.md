Challenge for the XSS prevention quest !

1/ Add :
`<meta http-equiv="Content-Security-Policy" content="script-src 'self' code.jquery.com 'unsafe-inline';"/>`

2/ XSS vulnerabilities 1 to 3 :
Replace `innerHTML` by `textContent`

3/ XSS vulnerability 4 :
Replace `document.location = redir;` by `window.location.replace(redir);`
