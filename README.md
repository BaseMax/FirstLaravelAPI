# FirstLaravel

### Insert fake/sample data to database

**$ php artisan tinker**

```
Psy Shell v0.10.7 (PHP 8.0.3 — cli) by Justin Hileman
>>> $post = new Post;
[!] Aliasing 'Post' to 'App\Models\Post' for this Tinker session.
=> App\Models\Post {#3329}
>>> $post->title = 'My first post'
=> "My first post"
>>> $post->content = 'My first blog post text...'
=> "My first blog post text..."
>>> $post->save()
=> true

>>> $post = new Post
=> App\Models\Post {#3322}
>>> $post->title = 'My second post'
=> "My second post"
>>> $post->content = 'My second blog post text'
=> "My second blog post text"
>>> $post->save()
=> true
```

## Acknowledgment

I saw an Youtube video and It's encouraged me to write a similar project myself.

© Copyright Max Base 2021
