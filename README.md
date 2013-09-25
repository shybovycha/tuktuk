# tuktuk 0.8.0
### Simple (but powerful) RWD Framework

More info in http://tuktuk.tapquo.com , [Source code](https://github.com/soyjavi/tuktuk) and [issue tracking](https://github.com/soyjavi/tuktuk/issues) are available on Github.

### Building

You must have `nodejs` installed. It's a requirement to proceed with building.

Then install the **Grunt** building tool: `[sudo] npm install -g grunt-cli grunt-coffee`.

Now, update the submodules to fetch **Stylus**-based dependencies: `git submodule init` and `git submodule update`.

Now, to build the TukTuk sources, first run `[sudo] npm install`. This will install all the dependencies.

Then run `grunt`. This will compile tuktuk sources to `site/package` directory.

## Credits
Created by [Javier Jiménez](http://twitter.com/soyjavi).
Copyright (c) 2011, 2013

### Licensing Options
TukTuk released under MIT license. See LICENSE.md for more information.
