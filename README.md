SynchKnot
=========

Testing for SynchKnot multi-protocol synchronization repacker

This is the planning area for now.

Goals
-----

Provide a syncronization storage area on high speed systems able to help repack data for 
mobile users.

Mobile isn't the only target.  Having faster access to data synchronized elsewhere is a 
bonus for everybody.

Once you start using it.. you should start saying "boop! done!" whenever you synch.

Target Protocols
----------------

- IMAP(S)

- SMTP(S)

  This would be an exaple of a reverse synch.

- Social Networks

  - Facebook

    Am I right?

  - Twitter

- Syndication

  - RSS

  - ATOM

What good does it do?
---------------------

Being able to repack data into a single packet stream (knots) for immediate commit to 
local storage is incredibly useful.  Think about tools like Unison where a state is 
stored both locally and remotely and deltas can be quickly made.

Would Facebook/Twitter adopt this?
----------------------------------

Heck no.  But unofficial apps are 'empowered' to utilize this service.

Service model
-------------

Applications utilizing this service would have to support a URL 'per account' so to 
speak and would have the option of supporting multiple accounts per app.  Accounts are 
via URL rather than a specific published service.

It can be hosted by highly availabe providers for free or $$$.  I will probably host it 
for a monthly low fee.

Self hosted on your own servers.. in the cloud.. 100% local.. whatever.
