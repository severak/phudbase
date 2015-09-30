PHudBase is the result of nearly five years of development on a PHP-based MUD-style game engine.

PHudBase-server is a PHP-CLI script that establishes one or more socket servers using customizable SocketServer and SocketClient classes.  It supports Telnet, HTML5 WebSockets, and Flash Sockets for communication.

PHudBase-client is a very simple implementation of HTML5 WebSockets (with a Flash client fallback for browsers that don't support WebSockets) and is intended merely as a demonstration of the server component.

PHudBase is designed to support game engines with client push capability making use of no plugins (Flash, Java, etc.) and is being implemented in one such game already.


---


PHudBase-WebMud is a derivative of the package designed to run alongside existing MUD servers and provide the same HTML 5 WebSocket client for existing games with no need to modify the game's code.  More details can be found at http://www.phudbase.com/webmud.php


---


Big thanks to http://code.google.com/u/georgenava/ for the release of phpwebsocket (http://code.google.com/p/phpwebsocket/), which got my WebSocket implementation going.