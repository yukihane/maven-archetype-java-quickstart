# What's this

Java8 Maven archetype.

https://maven.apache.org/guides/mini/guide-creating-archetypes.html
を参考に書いた, java21 向け quickstart archetype です.

# Install

    mvn clean install
    mvn archetype:update-local-catalog
    mvn archetype:crawl

# Usage

ex)

    mvn archetype:generate

(listed bottom row)

    mvn archetype:generate -DarchetypeCatalog=local

(listed only in local catalog)

    mvn archetype:generate -DarchetypeGroupId=jp.himeji-cs.maven.archetype -DarchetypeArtifactId=java21-quickstart

and so on.
