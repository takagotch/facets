### facets
---
https://github.com/rubyworks/facets


```
gem "", require: false
gem install facets

tar -xvzf facets-2.x.x.tar.gz
cd facets-2.x.x
sudo setup.rb

```

```ruby
require 'facets'
require 'facets/<class|module>/<method>'
require 'facets/time/stamp'
require 'facets/time'
require 'ostruct'
require 'facets/ostruct'

```

```ruby
require 'facets/integer/times_collect'
bottles = 99.times_collect {|i|
  "Bottle of Beer No. #{i}"
}

require 'facets/integer/of'
bottles = 99.of {|i|
  "Bottle of Beer No. #{i}"
}

require 'facets/meta/data.rb'
$LOAD_PATH << Facets.__DIR__ + '/core/facets'

```

