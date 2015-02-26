### 1.2.0

* Requires xamarin-test-cloud ~> 1.0; use 1.1.9 for older versions
* Support for XTC teams and organizations
* Obscure XTC API token and user name when logging

### 1.1.9

* Fix errant include in lib/irbrc.rb

### 1.1.8

* Tracking issues on pivotal: https://www.pivotaltracker.com/n/projects/1255750
* #36 briar resign can resign .ipas with swift dylibs

### 1.1.5

* Improves iOS 8 alert and sheet handling.

### 1.1.2

* Bump calabash version to ~> 0.10
* Adds support for targeting XTC series.
* Can now wait run xtc as async or sync.
* Adjusts how and when bundler is called when submitted an XTC job.

### 1.1.1

Bad release; see 1.1.2.

### 1.1.0

* Improves `briar install [device]` and `briar xtc` commands.
* Drop support for ruby 1.8.7.  The minimum version is 1.9.3.
* #8 added language keys for Danish and Thai @crishoj
* #12 briar now retries ideviceinstaller commands on failures
* #13 briar xtc command now executes all commands in the context of `bundle exec`
* #14 briar is dropping support for ruby 1.8.7

