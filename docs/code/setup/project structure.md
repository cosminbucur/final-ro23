# documentation
```
docs
    1 plan
        backlog
            1 TODO
                sample.md
            2 PROGRESS
                sample.md
            3 DONE
                sample.md
        backlog.md
        board.md
    2 design
        design.drawio
        routing.drawio
    3 infrastructure
        database model.drawio
        database model.mwb
```

# backend
```
src.main.java.com.sda.project
    config
        security
            SecurityConfig
            UserPrincipal
            ErrorHandler
            CustomAccessDeniedHandler
        web
            WebConfig
            SpringFoxConfig
        DbInit
    controller
        HomeController
        UserController
    service
        UserService
    repository
        UserRepository
    dto
        UserDto
    AgileApp
    
src.test.java.com.sda.project
    integration
        ProjectServiceIT
    service
        ProjectServiceTest
    AcceptanceTest
```

# frontend
```
src.main.resources
    static
        css
            main.css
        images
            logo.png
        js
            main.js
        favicon.ico
    templates
        error
            access-denied.html
        fragments
            footer.html
            footer-js.html
            head-css.html
            header.html
            sidebar.html
        user
            register.html
            forgot-password.html
        project
            projects.html
            project-add.html
            project-edit.html
        error.html
        login.html
        home.html
        index.html
    application.yml
```