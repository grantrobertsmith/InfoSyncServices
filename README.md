# InfoSyncServices

##Big Picture

The aim of this project is to automate human location awareness based on an individual's desire regarding the extent to which ze determines that zer location should be known by others. When in doubt, the information should be hidden and the individual should be prompted to provide access to that information.

###Puzzle Pieces
0. Automated Address Syncing
1. Personal(izable?) Information Distriution Contols
2. Trust Standards
3. Location Awareness
4. Minimized, Intelligent Human-Pinging

##Current Work

As a basic piece of the project, allow individuals to setup a source location (effectively a website and ulitmately a physical device) and allow them to specify destination locations to which the source information should be synced automatically whenever the source is updated (or according to any user preferences). This roughly corresponds to piece 0 above. This is approximately accomplished by mydex.org, a UK based non-profit organization; mydex forces the physical storage to remain under their its control, likely to acheive and be able to gaurantee and verify a level of protection on the information. With this in mind, we have reached out to mydex in order to understand to what extent its services can be used to rely on physical devices outside of its direct control.

In the mean time, piece 0 will be built as a proof of concept to sync mydex, google+ and facebook information as those services are already free and open and likely provide suitable api for automation of the process. Concurrently, additional platforms with public api should be investigeted and added. Ideally, it would be possible to use a single service, such as mydex.org to view and control all of one's personal information sharing. In making this service, it will therefore be ideal to centralize that control in mydex if possible or to replicate the control mechanisms provided by mydex if necessary.
