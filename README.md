# What's this

Java8 Maven archetype.

https://maven.apache.org/guides/mini/guide-creating-archetypes.html
を参考に書いた, java8向けquickstart archetypeです.

# Install

    mvn clean install
    mvn archetype:update-local-catalog
for update `~/.m2/archetype-catalog.xml`.

# Usage

ex)

    mvn archetype:generate 
(listed bottom row)

    mvn archetype:generate -DarchetypeCatalog=local
(listed only in local catalog)

    mvn archetype:generate -DarchetypeGroupId=com.github.yukihane.maven.archetype -DarchetypeArtifactId=java8-quickstart

and so on.
