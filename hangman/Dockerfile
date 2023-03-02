FROM ivanbo97/hangman-game:latest
COPY hangmand-config.yml /application/hangman-config.yml
ENTRYPOINT ["java", "org.springframework.boot.loader.JarLauncher","--spring.config.location=file:///application/hangman-config.yml"] 

