# SDN Traffic Monitoring Project
This project uses the Ryu Controller and Mininet to monitor network traffic in real-time.

## How to Run
1. Run the controller: `ryu-manager traffic_monitor.py`
2. Start Mininet: `sudo mn --topo single,3 --mac --controller=remote --switch ovs,protocols=OpenFlow13`

## Results
Check the screenshots for proof of ping connectivity and iperf throughput statistics.# SDN-Traffic-Monitor
