This project is for the Cloud DevOPS Nanodegree from Udacity. The aim of the project is to create a Cloudformation script that creates a network infrastructure and instance configuration to deploy a high-availability web app.

The script creates 4 instances in a private subnet then makes use of a load balancer to distribute the load on the 4 instances deployed as shown in the attached architecture diagram.
A Bastion (Jump Box) instance is employed to access the main instances as they don't have public IPs and can be accessed within the local network.

The DNS URL for the load balancer can be used to access the web app, the URL can be found in the "Outputs" tab in the Cloudformation stack view.

The parameters file contains variables that can be easily edited to provide flexibility and reusability to the script.
