# Laravel Homestead Vaprobash scripts

1. Add vaprobash.rb to the homestead/scripts directory
2. Unomment the scripts you'd like to run in vaprobash.rb.
3. Add the following to the end of the Vagrantfile in your homestead directory

```ruby 
require path + '/scripts/vaprobash.rb' 
```

Official Laravel Homestead documentation [is located here](http://laravel.com/docs/homestead?version=4.2).

https://github.com/fideloper/Vaprobash
