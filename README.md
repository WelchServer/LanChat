# LanChat
A Local Area Network service that allows for basic no-nonsense message and file transfer over local/private IP addresses.

V1.0:
  Install the zip, unpack, run LanChat.exe inside the folder.
  
  Enter Name (any name) and the IP address of the computer you would like to reach, that computer will need to do the same but with your IP address.
  
  It is worth it to note that WelchServer's LanChat (as of v1.0.0) has no peer authentication or encryption so any reachable host that can talk to those ports can potentially interact with it and it is not to be trusted on public networks.
  
  In its current state, it also does not verify the data being transferred at any moment, meaning any faults or errors in transfers will remain unnoticed by the software.

  The theoretical file transfer limit of this application is roughly 9.2 Exabytes, so the real limit should remain your local network capabilities.
