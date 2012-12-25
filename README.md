Crawljax mvn-repo
=================

Mainly used as a repository for dependencies that are currently not (or cannot be made) availabe in official public Maven repositories.

To use this repository add the following to your pom.xml:

    <repositories>
      <repository>
        <id>crawljax.mvn.repo</id>
        <url>https://github.com/crawljax/crawljax-mvn-repo/raw/master</url>
        <snapshots>
          <enabled>true</enabled>
          <updatePolicy>always</updatePolicy>
        </snapshots>
      </repository>
    </repositories>
