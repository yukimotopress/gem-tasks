---
title: Appendix - Hello, Hoe! Sample Sources
---

## Directory Structure

Full source code listings for the `hellohoe` gem:


```
|   README.txt
|   History.txt
|   Manifest.txt
|   Rakefile
|
\---lib/
      hellohoe.rb
```


## README.txt

```
= hellohoe

* https://github.com/planetruby/hellohoe

== DESCRIPTION:

Sample on how to use Hoe Rake tasks to build, package and publish gems.

== LICENSE:

The hellohoe sources are dedicated to the public domain. Use it as you please with no restrictions whatsoever.
```



## History.txt

```
=== 0.1 / 2020-03-05

* Everything is new. First release.
```


## Manifest.txt

```
History.txt
Manifest.txt
README.txt
Rakefile
lib/hellohoe.rb
```

## Rakefile

```ruby
require 'hoe'
require './lib/hellohoe.rb'

Hoe.spec 'hellohoe' do
  self.version = HelloHoe::VERSION

  self.author  = 'Gerald Bauer'
  self.email   = 'gerald.bauer@example.com'
end
```


## lib/hellohoe.rb

```ruby
class HelloHoe

  VERSION = '0.3'

  # your code here
end
```
