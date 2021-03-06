Omnomhub
========

Omnomhub is thought to be a recipe site for people who like to alter
recipes, if ever so slightly. Like Github, but for cooking. There are a
lot of copies of recipes where people slightly alter them to match their
dietary needs or tastebuds, at omnomhub you will always be able to see
the original recipe, and if you want - Make your own version of it. Just
like in github you can also collaborate on recipes, discuss and suggest
changes to make them better.


How to install
--------------

1. Install the following:

    * [Vagrant][] (As of writing version 1.4.2 works)
    * [VirtualBox][] (As of writing version 4.3.6)
    * [Ansible][]
    * [Composer][]

2. Run `composer install`

3. Add the following line to `/etc/hosts`

        192.168.13.37	omnomhub.dev

4. Run `vagrant up` to start the virtual machine.

5.  Visit http://omnomhub.dev/ to see Omnomhub in action.

    To access the Neo4J browser you can go to http://omnomhub.dev:7474


Need help?
----------

In case of problems don't hesitate to create an issue or:

* Join our irc channel #omnomhub on irc.freenode.net
* Join our [Facebook page][]
* Contact [@omnomhub on Twitter][]

Enjoy, and keep omnomming! :)

[Vagrant]: http://www.vagrantup.com/downloads.html
[VirtualBox]: https://www.virtualbox.org/wiki/Downloads
[Ansible]: http://docs.ansible.com/intro_installation.html
[Composer]: http://getcomposer.org/doc/00-intro.md
[Facebook page]: https://www.facebook.com/omnomhub
[@omnomhub on Twitter]: https://twitter.com/omnomhub
