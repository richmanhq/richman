richman is an choreography management platform like kubernetes, but richman operates at the level of application, not pod/container.

It "owns" some of your hardware resources such as CPU, GPU, memory, harddisk and network bandwith, and allocate to the application you request it to run.
This also means you can't use these resources by yourself, ok, you're warned.

richman can be run on a cluster (be very "rich"), richman application should also be cluster aware, 

