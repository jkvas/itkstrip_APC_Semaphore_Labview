# itkstrip_APC_Semaphore_Labview
simple handshake with the APC PowerChute 

The PowerChute server needs to be configured to create a semaphore file when critical condition is detected. 

Create a new .cmd file in C:\Program Files (x86)\APC\PowerChute Business Edition\agent\cmdfiles
and add:

> copy NUL c:\Users\Public\SystemWillShutdown
