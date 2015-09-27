<a href="http://projectdanube.org/" target="_blank"><img src="http://projectdanube.github.com/xdi2/images/projectdanube_logo.png" align="right"></a>
<img src="http://projectdanube.github.com/xdi2/images/logo64.png"><br>

This is a [secp256k1](https://en.bitcoin.it/wiki/Secp256k1) crypto plugin for the [XDI2](http://github.com/projectdanube/xdi2) client and server.

### Information

For examples, see [xdi2-example-secp256k1-client](https://github.com/projectdanube/xdi2-example-secp256k1-client), [xdi2-example-secp256k1-server](https://github.com/projectdanube/xdi2-example-secp256k1-server).

* [Code Example](https://github.com/projectdanube/xdi2-crypto-secp256k1/wiki/Code%20Example)
* [Server Configuration Example](https://github.com/projectdanube/xdi2-crypto-secp256k1/wiki/Server%20Configuration%20Example)

### How to use

Maven repository for releases:

	<repositories>
		<repository>
			<id>XDI2</id>
			<name>XDI2-releases</name>
			<url>https://artifactory.xdi2.org/xdi2-releases-local</url>
		</repository>
	</repositories>

Maven repository for snapshots:

	<repositories>
		<repository>
			<id>XDI2</id>
			<name>XDI2-releases</name>
			<url>https://artifactory.xdi2.org/xdi2-snapshot-local</url>
		</repository>
	</repositories>

Maven dependencies:

	<dependencies>
		<dependency>
			<groupId>xdi2</groupId>
			<artifactId>xdi2-crypto-secp256k1</artifactId>
			<version>... version here ...</version>
			<scope>compile</scope>
		</dependency>
	</dependencies>

### Community

Website: https://xdi2.org/

Google Group: http://groups.google.com/group/xdi2

Weekly Call: [Thursdays at 4pm US Eastern Time](https://github.com/projectdanube/xdi2/wiki/XDI2-Weekly-Call)

IRC: [irc://irc.freenode.net:6667/xdi](http://webchat.freenode.net?randomnick=1&channels=%23xdi)
