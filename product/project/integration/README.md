# communication protocols and integration principles

We need something SET IN STONE to assure working modularity. 

If we use APIs -- we need to keep in mind the routes: api version, 
never removing old version (backward compatibility), breaking and
non-breaking changes... 

Ideally, we plan this WELL (waterfall?) -- to avoid any breaking
changes in the CI/CL flow

Protocols are **comunnication** rules that keep the system alive,
like the neurons in the body. Backend without protocols for the front end is dead meat...