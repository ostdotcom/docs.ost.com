# Reference links
https://docs.antora.org/
https://gitter.im/antora/users
https://gitter.im/antora/dev

## Build site
Navigate to your site folder and run

`antora playbook.yml --fetch`

This will generate the site with the default Antora site generator. From there, open the path to the index.html file in your browser. (You can find this in the public folder.)

### To run a local server

1. Install the serve package globally using npm:
`npm i -g serve@6.5.8`

2. Launch web server
`serve build/site`