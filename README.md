# INSTALL-AND-CONFIGURE-ELK-IN-JUST-3-STEPS
INSTALL AND CONFIGURE ELK IN JUST 3-STEPS:



STEP-1: Download the github repository
	git clone https://github.com/sunilkvasu/install_elk.git

STEP-2: Customize ansible inventory variables
	vi inv

STEP-3: Run the playbook
	ansible-playbook -i inv main.yaml

