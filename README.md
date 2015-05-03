> **Note**: This branch (master) contains a skeleton without any app code, perfect for creating a _new_ application or challenge.

### Purpose
The Sinatra Skeleton:

Provides an MVC foundation for creating a new Sinatra application.

### Quickstart

1.  `bundle install`
2.  `shotgun config.ru`

As needed, create models & migrations with the `rake` tasks:

```
rake generate:migration  # Create an empty migration in db/migrate, e.g., rake generate:migration NAME=create_tasks
rake generate:model      # Create an empty model in app/models, e.g., rake generate:model NAME=User
```