# Helpful Rails Terminal Commands!

# 1. Create a new rails app
```rails new app_name -G --database=postgresql```
 * `-G`: does not create `.git` repo
 * `--database=postgresql`: sets database to be postgresql not sqlite

# 2. Create a new rails app with a specific version
```rails _5.2.3_ new app_name -G --database=postgresql```

# 3. Create your rails app database
```rails db:create```

# 4. Generate a migration
```rails g migration MigrationName```

# 5. Generate a model
```rails g model ModelName```
 * generates a model and migration file
 * ModelName should be singular

# 6. Run your migrations
```rails db:migrate```

# 7. Check migration status
```rails db:migrate:status```

# 8. Drop your database! **BE CAREFUL**
```rails db:drop```
 * Will get rid of all data stored in database

# 9. Seed your database based on `seeds.rb` file
```rails db:seed```

# 10. Setup your database
```rails db:setup```
 * runs `rails db:create`, `rails db:schema:load`, `rails db:seed`

# 11. Generate a controller
```rails g controller ControllerName```
 * Controller name should be plural

# 12. See your routes
```rails routes```

# 13. Start your rails server
```rails s```

# 14. Access rails console
```rails c```