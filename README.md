# honeyfs
LLM Based Honeypot File System Creator

Honeypots that can be configured to replicate file systems, configurations and so on can benefit from the use of LLMs and other ML technologies in the creation of lures, files, context, and even complete file systems. Looking at the popular SSH and Telnet honeypot cowrie, the configuration allows for a honeyfs visible to an “authenticated” attacker, and careful crafting of this data will enable analysts to target or improve engagement with specific threat actors.

The following is a simple PoC that creates a fake file system using GPT3.5 and some prompt engineering. It is not intended for production usage.
