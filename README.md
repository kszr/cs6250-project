# cs6250-project
##Setup
1. Download the OVA file from http://sdnhub.org/tutorials/sdn-tutorial-vm/.
2. Open the VM on VirtualBox or another VMM. (Username and password are both "ubuntu".)
3. Clone this repository:

    ```
    git clone https://github.com/kszr/cs6250-project.git
    ```
4. Delete existing ```~/ryu``` directory and install ```cs6250-project/ryu``` (this step not really necessary):

    ```
    rm -rf ~/ryu  
    cd ~/cs6250-project/ryu  
    sudo python setup.py install
    ```

##Built-in Mininet topologies
* http://mininet.org/api/classmininet_1_1topo_1_1Topo.html

##Additional References
* http://sdnhub.org/tutorials/ryu/
* http://ewen.mcneill.gen.nz/blog/entry/2014-08-31-ryu-on-ubuntu-14-04/ 
* http://ryu.readthedocs.io/en/latest/writing_ryu_app.html
