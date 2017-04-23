# PomArguments

<build>
    <sourceDirectory>src</sourceDirectory>
    <resources>
        <resource>
            <targetPath>.</targetPath>
            <filtering>true</filtering>
            <directory>src</directory>
            <includes>
                <include>*.yml</include>
            </includes>
        </resource>
    </resources>
    <finalName>Tutorial</finalName>
</build>
<repositories>
    <repository>
        <id>spigot-repo</id>
        <url>https://hub.spigotmc.org/nexus/content/repositories/snapshots/</url>
    </repository>
</repositories>
<dependencies>
    <!--Spigot API-->
    <dependency>
           <groupId>org.spigotmc</groupId>
           <artifactId>spigot-api</artifactId>
           <version>1.8.8-R0.1-SNAPSHOT</version>
           <scope>provided</scope>
    </dependency>
    <!--Bukkit API-->
    <dependency>
            <groupId>org.bukkit</groupId>
            <artifactId>bukkit</artifactId>
            <version>1.8.8-R0.1-SNAPSHOT</version>
            <scope>provided</scope>
    </dependency>
    <dependency>
        <groupId>org.github.paperspigot</groupId>
        <artifactId>paperspigot-api</artifactId>
      <version>1.8.8-R0.1-SNAPSHOT</version>
      <type>jar</type>
    </dependency>  
</dependencies>

