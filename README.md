# Ubicomp-exercise-2
Task 1:
Notebook with experimental results for the Offline Gaze Data Analysis for Activity Recognition and experiment report can be found in the files

Task 2+3:
During the implementation of task 2 and 3 i experienced multiple pittfalls and obstacles which ultimately lead to not being able to fully finish those tasks completely

First of all i had trouble with connecting the Computer to the Eduroam network of the university. Since the device has no Wifi or bluetooth receiver i could only connect it via Ethernet to Eduroam.
Since i have no display at home i opted to do my work from the HCI labs at Torstrasse. There Ethernet ports and displays are provided. Aftermultiple times of trying to connect it to the Ethernet port, someone from IT told me that it can be only used with special Ethernet port which still run on the unisg network and not the new network for some reason. Luckily at HCI i could find two of those ethernetports.

The next Pitfall was when i tried to test the holographic remoting after playing a bit in unity. Since the Hololens and the Computer are not in the same local network this is not possible. In the beginning i did not realize that both HSG networks are different networks and spend some time finding this out. My second option was to deploy it via build to the Hololens, but here again they have to be in the same network. Luckily Lukas told me that he has a Wifi-stick at home which he brought the following week so that i can connect the Hololens and Computer to the same network.

My idea for the activities and actions i had based on the Gaze data were following:
Reading: A UI panel that says, "If you would like me to look up a word for you, simply say that word!" and then Integrate with the dictionary API and use Unity's UnityWebRequest to fetch the dictionary entry for the spoken word.
Inspection: A UI panel asking if the user wants to see a 3D model of the inspected piece and then open a webpage for 3D-object
Search: A UI panel asking if the user needs assistance searching for an item. Then opening a webbrowser where the User can search
I started with the implementation of those elements in Unity, created the UI elements for them and also the UnityWebRequest and actions.
The  WebLauncher library could not be imported properly for some reason and i couldnt finish the actions.

Gazedata:
I had big troubles accessing the gaze data. I tried to access it via the ARETT script, described like in the slides but it just would not work. I ultimately could not access the data for some reason. 









