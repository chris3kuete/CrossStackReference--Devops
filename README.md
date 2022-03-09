# CrossStackReference--Devops
Reference Resources from another stack

This project deploys a sample network configuration stack called SampleNetworkCrossStack.
Then Deploy a new stack that will setup a Linux EC2 instance and reference the sample network stack previously created.
The new stack:
            -references all available variables from SampleNetworkCrossStack
            -Creates a Mapping function to dynamically choosing regions
            -Allocates an Elastic IP address using resources
            -Creates parameters for requesting user inputs
            -Outputs the values of the private IPV4 address and DNS name of the instance
            -Install and configure apache on the EC2 using User data to display my name on a webpage
