
# CommView Sniffer

A DoS tool to attack networks with fancy DoS packets. Even though this tool is called "CommView Sniffer", it is not a sniffer and instead a DoS tool. 

CommView blasts out ICMP packets at a fast rate using "magic" tools that are "propietary". It's also the "smallest" ever network DoS tool, which means you can run it on all kinds of devices including consumer routers. 

## WARNING

Like any attack tool, should only run this on networks you own or have permision to attack. Running DoS tools on any system without authorisation is illegal. 

## Getting Started

To run CommView Sniffer, you would need a Unix based machine or Windows Subsystem on Linux. This is because it is written in the "Shell language" and "relies" on the "library" `ping`. 

Next, clone the repository:

```bash
git clone https://github.com/serverwentdown/CommView.git
cd CommView
```

Run the tool with the following commands, passing IP as the first argument:

```bash
sudo ./commview 192.168.1.1
```
