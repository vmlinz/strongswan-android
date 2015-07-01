# Strongswan Android app preconfigured for hacking #

Strongswan Android app imported as gradle project and setup for hacking

# How to build it #

[Build the strongswan vpn client for Android](https://wiki.strongswan.org/projects/strongswan/wiki/AndroidVPNClientBuild)

* Download the release source package and extract to jni folder
* Fetch android ssl modified by strongswan with static linking
* Install latest ndk tools on your machine
* Build the native parts
* Run the project in Android Studio or using gradlew scripts

# Prepare the source #

* `cd dir_of_strongswan && ./autogen.sh && ./configure && make dist`

# Customize the client #

# References #

