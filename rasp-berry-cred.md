#Setting up a DCR full-node for non-devs

Some weeks ago, we decided to set up a Decred full-node at our office. There are no developers in our team, we are just a bunch of people with design and communication backgrounds so it presented a bit of a challenge. Fortunately, everything is well documented on Github and the Decred site. The node is now up and running. This was our experience.

Research

In Crypto Rocket we like to get our hands on every project we do communications for. Decred is one of them. We wanted to get involved with the network and decided that setting up a node would be the best way to do it.

The first thing we did was to look up for the node software at the Github repo. We found two ways of doing it: setting up Decrediton and use the GUI like most users would or go full-dev style and show-off my basic command line skills at the office.

So I brewed myself some good ol’ mate and started tinkering with an Ubuntu terminal from my Windows PC. I wanted to get the software running on my laptop before trying to set up the node on the definitive piece of hardware.

I surfed Decred’s website, ended up in Github and found dcrd, the Decred daemon software. dcrd is a full-node implementation, meaning it hosts a full copy of the Decred blockchain, written in Go, a programming language developed by some people at Google who wanted a better language for building cloud solutions.

At first, I tried to build dcrd from source, but after installing Go, my plan went south and I could not make it work. But hey, that’s why we have the Linux binaries ready for download.

https://github.com/decred/decred-release/releases/tag/v1.4.0

Just connect to the network, please

Great, I have the software. For those who have not struggled with Linux before tackling a full-node project, files must be given execution attributes before running them. Running “chmod u+x dcrinstall-$ARCH-$VERSION” before running it with “./dcrinstall” gets the job done.

The first thing dcrinstall will do is set up a mainnet wallet. It will ask the user for a passphrase for the new wallet.

After that, dcrd will be up and running. But, wait, we must download and validate the whole blockchain before the node can really help decentralize the network. Currently the Decred blockchain requires 3.25 GB of free space. Coming from Bitcoin and other crypto projects, I was surprised. Just 3.25 GB means that I don’t need to install an external drive for the node to run. I remember it as a painful process so I got quite happy about it.
The node started downloading the Decred blockchain. My work could be done, but I wanted it to run 24/7 nonstop and my laptop is always going places, so I started the third phase of the plan.

Rasp-berry-cred

I’m the proud owner of a little Raspberry Pi 3+ since 2016, which I use for several DYI projects (bots, a failed media-center at home, and just tinkering with Debian). This small computer quickly became my go-to hardware for setting up nodes.

For those who are considering getting one, the new Raspberry Pi 4 costs $35, a cable and a charger,, $10, 16 GB Micro SD, $10; plus the shipping costs.

For those like me who first tested the software on their personal computers, keep in mind that smaller computers like Raspberry Pi have a different architecture. While most “regular” computers have x64 and x86 chips, the Raspberry Pi has an ARM architecture and users must install the ARM version of the software. Otherwise it won’t run. (It got me a while to learn this. Clap twice if I saved you some time).

The Raspberry Pi at the office is running Raspbian, a Raspberry Pi version of Debian, a popular Linux distribution. The OS can be installed by downloading the image from the official Raspbian site and installing it in the Micro SD card with something like Balena Etcher.

https://www.raspberrypi.org/downloads/raspbian/

The last step is to repeat the install on the Raspberry Pi, downloading dcrinstall from Github and running the software. No matter how fast your connection, the node will take its time to download the whole blockchain. While the download may be fast as hell, the Raspberry Pi smaller chip requires more time to process and check that every block fits the previous hash and verify it.

If you’ve followed the whole post to set up your own node, give yourself a pat in the back and pour another drink o brew more mate, you are now contributing to the Decred network in the best way possible, keeping a copy of the whole chain.

Happy staking.
