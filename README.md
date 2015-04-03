# upcoming-www

Upcoming.org 2.0 Web Site

First version is monolithic PoC, but main functionality will eventually migrate to upcoming-core API and other components.

You can see the contributed INSTALL.md for quick and dirty setup, however an Ansible playbook is coming (this will likely be in a separate repo, referenced by the [upcoming meta-project](https://github.com/upcoming/upcoming))

## Contributor Notes
We happy to take pull requests, although things are quite unstable at the moment. Worth noting, the code is *not* PEP8 compliant. Specific differences:
* We use 2 spaces for indenting (:set expandtab tabstop=2 shiftwidth=2 tabstop=2)
* imports are alphabetized, from has extra spaces to align package names
* 2-linebreaks used for methods
* ### is used to denote sections, # is used for comments

## License
This project is released under the Apache 2.0 license. See the LICENSE file for the legal boiler-plate.
