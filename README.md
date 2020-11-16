
# CommView Sniffer

A DoS tool to attack networks with fancy DoS packets. 

## WARNING

You should only run this on networks you own or have permision to attack. Running DoS tools on any system without authorisation is illegal. 

## Getting Started

To run CommView Sniffer, you would need a Unix based machine or Windows Subsystem on Linux. This is because it is written in the "Shell language" and "relies" on the "library" `ping`. 

Next, clone the repository:

```
git clone https://github.com/serverwentdown/CommView.git
cd CommView
```

Run the tool with the following commands, passing IP as the first argument:

```
sudo ./commview 192.168.1.1
```
