# Rubocop Gem

## How to setup

1. Create ~/.gem/credentials file with:
```sh
---
:rubygems_api_key: #get from gitlabs productionE/rubygems.yml
```

## How to build and release

```sh
# 1. Turn on the rule in .rubocop.yml that you want to engage.
# 2. Bump up gemspec version number
# 3. Build the gem.
> gem build kalkomey-rubocop.gemspec
# 4. Publish the gem.
> gem push kalkomey-rubocop.gemspec
# 5. Delete the gem created in step 3.
# 6. Push your changes to master.
```
