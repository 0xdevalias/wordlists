# wordlists

A place to store my own wordlists, and link to others that are useful

## SecLists

* https://github.com/danielmiessler/SecLists
    * "SecLists is the security tester's companion. It is a collection of multiple types of lists used during security assessments. List types include usernames, passwords, URLs, sensitive data grep strings, fuzzing payloads, and many more."
    * Massive collection of wordlists.. but comes in pretty weighty (~320mb + git overheads) when you only end up using a couple of the lists..
    * https://github.com/danielmiessler/SecLists/tree/master/Discovery/Web_Content
    * https://github.com/danielmiessler/SecLists/tree/master/Fuzzing

## Big List of Naughty Strings

* https://github.com/minimaxir/big-list-of-naughty-strings
    * "The Big List of Naughty Strings is a list of strings which have a high probability of causing issues when used as user-input data."

## Drek / WatchTower (Static Code Analysis)

* https://github.com/chrisallenlane/drek
    * "A static-code-analysis tool for performing security-focused code reviews. It enables an auditor to swiftly map the attack-surface of a large application, with an emphasis on identifying development anti-patterns and footguns."
    * https://github.com/chrisallenlane/drek-signatures : Example signature files for drek
    * https://github.com/chrisallenlane/drek-signatures/issues/1 : Issue to merge Bishop Fox watchtower signature additions
    * https://github.com/chrisallenlane/drek-signatures/issues/2 : Issue to merge Java signature additions
        * https://github.com/schristiaens/drek-signatures: Fork with some extra additions
* https://github.com/chrisallenlane/watchtower
    * "(old, deprecated) : Watchtower is a Static Code Analysis tool designed to assist security auditors who are tasked with performing manual code reviews. It is platform- and language-agnostic.""
    * https://github.com/BishopFox/watchtower (fork, updated signatures)
        * https://github.com/BishopFox/watchtower/compare/c148caf4867d7eb5ddfa279d8e3186852f66e7f4...BishopFox:master seems to show the new things that were added
* Other potential sources of useful material
    * https://stackoverflow.com/questions/3115559/exploitable-php-functions
    * This may not be the most up to date source, but apparently RIPS maintained some good lists of sources/sinks
      * https://github.com/robocoder/rips-scanner/blob/master/config/sources.php
      * https://github.com/robocoder/rips-scanner/blob/master/config/sinks.php
      * https://sourceforge.net/projects/rips-scanner/files/ (download latest version and grab them from there)
