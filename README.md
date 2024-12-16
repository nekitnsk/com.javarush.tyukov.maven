Проверить что настроены java и mvn:
 java --version
 mvn -v
 
Сборка:
 mvn clean install
Установка jar -файла как зависимости в локальный .m2:
 mvn install:install-file -Dfile=D:/projects/project-maven-live/lib/desktop-game-engine.jar -DgroupId="com.javarush" -DartifactId=desktop-game-engine -Dversion="1.0" -Dpackaging=jar
Запуск jar-файла:
 java -jar "D:\projects\project-maven-live\target\project-maven-1.0.jar"

 Только подставьте свои пути к файлам
