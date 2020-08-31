#install ESXI6.7
#environment: ubuntu
#install GO and set the environment variable GOPATH
#install the latest govc:
	go get -u github.com/vmware/govmomi/govc
	go install github.com/vmware/govmomi/govc
#input the script in the terminal of ubuntu and make sure:
	  URL is the URL of the ESXI where you want to clone the OVA
	  USERNAME and PASSWORD is both about the ESXI
	  DETASTORE and NETWORK should be checked previously on the ESXI
#clone the OVA, which has been exported, to the ESXI
