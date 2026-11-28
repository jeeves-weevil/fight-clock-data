# Fight Clock schedule feed

The files a Fight Clock downloads, rebuilt every three hours:

    /v1/index.json          which promotions have events, and when this was built
    /v1/p/<promotion>.json  that promotion's upcoming events

Times are UTC. Every build replaces this repository's contents, so do not
edit it here. Not affiliated with or endorsed by any promotion; event
names are used only to identify the events.
