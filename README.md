# mes-bom

rm -rf ~/.m2/repository/com/xeline/

cd %BASE_PATH%\mes-bom
mvn -f pom_base.xml clean package install
mvn -f pom_jar.xml clean package install
mvn -f pom_war.xml clean package install
mvn -f pom_web_service.xml clean package install
