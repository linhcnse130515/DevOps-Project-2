udacity cloud devops engeneer project 2

What is it ?
The goal of thi project is to provide some cloudformation scripts to deploy web servers for a highly available web app.

how is the project cut out ?
there are two parts in this project - network scripts - servers scripts

what are the requirements to run it ?
Amazon aws account and a bucket already deployed having the web app code . Don't forget to adapt the userData to match your webapp sources location

how to run it ?
you can run the part as followed :

./create.sh [stackName1] network.yml network-parameters.json
./create.sh [stackName2] servers.yml servers-parameters.json
how to test that it works
here is the url for testing http://udapr-WebAp-5FGB55RT7GZY-661540103.us-east-1.elb.amazonaws.com/