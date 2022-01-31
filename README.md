# What's this

Java8 Maven archetype.

https://maven.apache.org/guides/mini/guide-creating-archetypes.html
を参考に書いた, java17向けquickstart archetypeです.

# Install

    mvn clean install
    mvn archetype:update-local-catalog

On [Mac](https://stackoverflow.com/a/48264940/4506703), additional:

    mvn archetype:crawl

for update `~/.m2/archetype-catalog.xml`.

# Usage

ex)

    mvn archetype:generate 
(listed bottom row)

    mvn archetype:generate -DarchetypeCatalog=local
(listed only in local catalog)

    mvn archetype:generate -DarchetypeGroupId=jp.himeji-cs.maven.archetype -DarchetypeArtifactId=java8-quickstart

and so on.
