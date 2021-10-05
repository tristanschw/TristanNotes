**Starting Anything**
1. catkin_make from the root
2. source devel/setup.bash from the root
3. roscore from a new terminal in the root

#PackageError 'Turtle_Patrol' not found: You need to run source devel/setup.bash from the root because you opened a new terminal.
1. rospack find package_name: locate package
2. rosls package_name: list contents of package
3. roscd package_name: go to package

#structerror: 'required argument is not a float' 
1. float numbers require a decimal
#Servers/Requests/Services
Function: To execute calls in sequence, synchronously (server node is always keeping up to date with the calls of the client and vice versa)
Method:
	1. A client node requests a service from a server node
	2. The server node receives the requests, fulfills the service call, and returns a response to the client
	3. The client node receives the response and proceeds to next steps.
	
ROS Definition: 
- **Service types** are defined in a **.srv file** and are typically found under the srv directory in a package
	- **.srv file** contains requests (located above the -- line) and responses (below the -- line)
	- requests are in the same format as the TimeStampString.msg file (infact, they are identical to the messages used in ROS Topics, for example:
	![[Pasted image 20210916093428.png]]
	- 
-**Service Nodes** are defined in a .py file.

![[Pasted image 20210916094445.png]]
[11-12] #wait_for_service() is used to block until a service is available (put this before you call a service using rospy.ServiceProxy)
	- rospy.wait_for_service(service, timeout=None) 

[14] #ServiceDefinition: A container for the request and response type. These must be used whenever we create or call a service. In this case, our Service Name is */turtle1/teleport_absolute* located in a **class** called *TeleportAbsolute*