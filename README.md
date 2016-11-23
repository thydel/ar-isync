# help use isync and mu

## minimal invocation (for a gmail account)

	./play.yml -e user=some.user@gmail.com

- Get lastest isync version, compile and install
- Install mu
- Generate a user config for isync

# isync: free IMAP and MailDir mailbox synchronizer

## links

* [sourceforge base](https://sourceforge.net/projects/isync/)
* [sourceforge git](https://sourceforge.net/p/isync/isync/ci/master/tree/)
* [sourceforge web](http://isync.sourceforge.net/)

## minimal invocation

	mbsync --pull some.user@gmail.com

# mu: fast indexing for Maildir

## links

* [site](http://www.djcbsoftware.nl/code/mu/)

## minimal invocation

	mu index
	mu find d:today..now NOT f:root
