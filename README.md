# netstatXplorer
The netstat command provides the informations needed to create a network map through TCP socket state. 
This repository provides : 
1) the web folder that have to publish into Apache - PHP/JAVASCRIPT/AJAX
2) the PERL script with its 2 templates (model.html and model.js) which permit the generation of static HTML pages showing the network.  
3) each script or command by environment (Windows / Linux / AIX) to get the informations from remote servers.

Each node represent a server name or an ip address and the edges correspond to the flows between each server.


External libraries used / Dependencies : 
- jQuery : 3.3.1
- Cytoscape.js : 3.5.0 (http://js.cytoscape.org/ - https://github.com/cytoscape/cytoscape.js)
- Cytoscape.js Panzoom (https://github.com/cytoscape/cytoscape.js-panzoom) 
- Cytoscape Navigator (https://github.com/cytoscape/cytoscape.js-navigator)
- Datatables (https://github.com/cytoscape/cytoscape.js-navigator)

Supported OS on "remote servers" :
- MS Windows 2008/2012 (PowerShell required)
- Linux (RedHat/CentOS/Fedora)
- AIX 

Requirements : 
- on Web Server : Apache with PHP
- on remote servers : sudo root rights on the netstat command (to get the processes name with -p argument)
