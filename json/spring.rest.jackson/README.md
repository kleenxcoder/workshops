# REST example using @JsonView
> @JsonIgnore is not always the best to use in your REST service. Still @JsonIgnore is the first choise of most developers. This takes a lot of flexibility. As a solution developers come up with different solution making code more complicated then it should be.

## Description
> This project has two entities (User, UserAction) having a one2many relation. We use two REST controller to query data. We do not use @JsonIgnore to avoid endless cycle loop. Instead we are using @JsonView to explicitly define the granularity we want to display.

## URL's
http://localhost:8080/h2-console/ </br>
http://localhost:8080/api/kleenxcoder/user/generate/ </br>
http://localhost:8080/api/kleenxcoder/user/ </br>
http://localhost:8080/api/kleenxcoder/useraction/ </br>