# ojdbc7
Oracle JDBC Driver for java oracle.jdbc.driver.OracleDriver ojdbc7


# how use
mvn clean install

rm .m2\repository\com\github\noraui\ojdbc7\12.1.0.2\ojdbc7-12.1.0.2.jar

cp .m2\repository\com\oracle\jdbc\ojdbc7\12.1.0.2\ojdbc7-12.1.0.2.jar .m2\repository\com\github\noraui\ojdbc7\12.1.0.2\ojdbc7-12.1.0.2.jar

mvn deploy -Pdeploy  (configure your Maven setting.xml)
