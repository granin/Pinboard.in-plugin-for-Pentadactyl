# Pinboard.in plugin for Pentadactyl Firefox plugin

This is basically just a cut and paste job on top of [Thedward Blevins' Pinboard adaptation](http://code.google.com/p/vimperator-labs/issues/detail?id=358) which is a basically just a cut and paste job on top of the wonderful [Delicious plugin by nikolai.weibull](http://code.google.com/p/vimperator-labs/issues/detail?id=241).

## Installation

See [Pentadactyl's plugin installation instructions](http://5digits.org/pentadactyl/plugins).

> Install these plugins by copying them to the
> ~/.pentadactyl/plugins/ directory
> (or %USERPROFILE%\pentadactyl\plugins on
> Windows).

## Usage

Use the `rinboard` command in Pendatactyl.

Shortcut `rin`

Such a name is used due to a conflict with the Pentadactyl "pintab" command.

### Sample usage

    :rinboard -description Description\ for\ current\ page tag1 tag2 .private-tag

    :rinboard tag1 tag-other -description "Another way to make a description"

### Pinboard API authentication

If asked by Firefox, enter your standard username and password for Pinboard. There's no need to create a separate API account.
