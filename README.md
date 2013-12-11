#What is this?

Cloak is a popular lightweight game server/client framework built 
over socket.io.  Sadly, cloak's client is not configured for use
with broserify and relies on a global "cloak", "io", and "_" being
available.  This module simply requires lodash and socket.io-browserify
and then uses module.exports to expose a cloak client instance.  

Yiss.
