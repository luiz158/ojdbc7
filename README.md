# ojdbc7
Oracle JDBC Driver for java oracle.jdbc.driver.OracleDriver ojdbc7


# how use
mvn clean install

unzip .m2\repository\com\oracle\jdbc\ojdbc7\12.1.0.2\ojdbc7-12.1.0.2.jar -d destination_folder

cp .m2\repository\com\oracle\jdbc\ojdbc7\12.1.0.2\ojdbc7-12.1.0.2\oracle target\classes\oracle

mvn deploy -Pdeploy -Dmaven.main.skip=true -Dmaven.install.skip=true  (configure your Maven setting.xml)
