<project>
    ...
    <reporting>
        <plugins>
            <plugin>
                <groupId>org.apache.maven.plugins</groupId>
                <artifactId>maven-pmd-plugin</artifactId>
                <version>3.21.0</version>
                <configuration>
                    <rulesets>
                        <ruleset>/rulesets/java/braces.xml</ruleset>
                        <ruleset>/rulesets/java/naming.xml</ruleset>
                    </rulesets>
                </configuration>
            </plugin>
        </plugins>
    </reporting>
</project>
