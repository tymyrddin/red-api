# Access to connected systems

APIs pull data from multiple other APIs and back-end systems. The architecture looks like the roots of a tree, 
and it is impossible to have access to every environment in this system. 
Emulation and mocking of inaccessible resources is usually chosen to avoid testing bottlenecks. For API testing, this 
does not reduce the load. It just pushes it to another place. Plus, emulating race conditions for performance and 
load testing may not be such a good idea.