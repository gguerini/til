# Running multiple Rake tasks

Sometimes you need to run multiple Rake tasks. One way to accomplish that is doing this:

```ruby
rake spec:models && rake spec:lib
```

But you can also do this instead:

```ruby
rake spec:{models,lib}
```
