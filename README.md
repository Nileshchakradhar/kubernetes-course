## Become a Cloud and DevOps Engineer

Learn every tool that matters: https://rayanslim.com



minikube service grade-submission-portal -n grade-submission

1. the above command should run if want to run the services because It's important to note that Minikube dynamically assigns a NodePort from a specific range (30000-32767 by default). If you're seeing a different port like 54299, it's likely that Minikube has assigned that as the temporary node port for the service.

2. to convert the plain text into the base 64 = echo -n "admin" | base64   these will return the base 64 code and that we have pass in the kubernetes configuration. Then kubernetes will again change it from base64 the plain text during the run time.

3. these is a file uploaded which consist of command in powershell used to install the metrics api to check the metrics data from the metric server.

4.  Uploaded another file that has the command to install the nginx ingress controller.



The steps to create helm package from the templates
1. helm package .
2. helm install (chart_name) (Package_name)
Now if we got any error while installing the package then uninstall the current package by using the below command
3. helm uninstall (chart_name)
   Now create the new package with our new step by using the command no. 1 and then install the chart by using the command no. 2
   
