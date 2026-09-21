ABOUT
=====

A radically simple Ansible Role.
- System: Debian 13
- State: probably production

TO DO
=====

Check variables, especially if
- tls_starttls

NOTES
=====

```sh
# test:
echo -e "Test Body" | sudo mail -s "Test subject" "unonweb-report@freenet.de"
```

mail.rc
-------

By default, core system utilities like mail, mailx, and smail look for a traditional Sendmail binary (/usr/sbin/sendmail) to deliver outgoing messages.
Setting `set sendmail=/usr/bin/msmtp` inside `/etc/mail.rc` redirects mailx / mail to use msmtp

msmtpd
------

- https://man.archlinux.org/man/extra/msmtp/msmtpd.1.en


LINKS
=====

- https://github.com/chriswayg/ansible-msmtp-mailer/blob/master/defaults/main.yml