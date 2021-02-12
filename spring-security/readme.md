1) добовление <parent> spring-boot-starter-parent
2) добовление <dependency> spring-boot-starter-web
3) добовление <build> spring-boot-maven-plugin
4) добовление <packaging>jar
5) структура
    src\\config — классы с конфигурациями для MVC (MvcConfig) и безопасности (WebSecurityConfig);
    src\\controller — классы с контроллерами;
    src\\entity — классы с моделями;
    src\\repository — интерфейсы репозиториев;
    src\\service — классы c сервисами для моделей;
    src\\webapp\resources — статические объекты: js, css, img;
    src\\webapp\WEB-INF\jsp — представления в виде файлов .jsp.
6)