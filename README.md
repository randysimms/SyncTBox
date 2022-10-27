# All About SyncTBox

Sync tool from source to TeraBox while encrypting and splitting files to maximize 1TB storage.

# Proof of Concept

 - At source on local:
	 - [x] Encrypt files with 7zip
	 - [x] ZIP or bundle files with 7zip
 
 - At TeraBox, use Windows client to prove:
	 - [x] Verify TeraBox accepts encrypted files and zip files.
	 - [ ] Verify maximum file size.
	 - [ ] Verify no timeouts.
	
# Features
 - Send files with automation
	 - [ ] Implement Rsync to send files 
	 - [ ] Split files into under 500 total files
	 - [ ] Some kind of GUI to choose files, encryption settings, etc.
	 - [ ] Scheduler...
