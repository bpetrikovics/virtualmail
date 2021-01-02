# Virtualmail - minimalist virtual mail server management

This is a Perl script I use to manage my personal e-mail system based on MySQL/Mariadb, Exim4,
dovecot IMAP, spamassassin/rspamd. The goal was to be able to manage an e-mail server without
having to hardcode domains or aliases into any config files, or having to add the mail users as
UNIX system accounts.

Nothing fancy or particularly professional, but might come handy for others some day. Yes, the
database "design" is very simplistic, but this is perfectly enough for me for a couple tens of
domains and users/accounts. If anyone's interested I might add the e-mail server configuration
bits as well at a later point, for now it's only the schema/admin script.

## Installation, dependencies, etc

You'll need to install a couple things either via CPAN or your distribution's package manager:

* Config::IniFile
* DBI
* DBD::MySQL

