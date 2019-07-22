## Deploy prometheus in Cloudfoundry ##

1. Using prometheus-2.11.1.linux-amd64 . Get latest package from https://prometheus.io/download/ 

2. Edit manifest.yml as per your requirement.

3. change directory to where you have cloned this git repo in your laptop. Example <code>git clone https://github.com/sharadchhetri/cf-prometheus.git && cd ~/cf-prometheus</code>

4. To deploy run <code>cf push</code> . Ref: https://docs.cloudfoundry.org/cf-cli/install-go-cli.html 
