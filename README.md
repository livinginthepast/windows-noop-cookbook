windows-noop-cookbook
=====================

This cookbook serves as a dummy placeholder for the `windows`
cookbook, which many other cookbooks depend on. If you don't
use Windows, it can be extremely annoying when bootstrapping
a host and watching tons of superfluous cookbooks being downloaded.

This cookbook does nothing, and it does so with a very small
amount of files.

## Usage

When using Librarian, add the following to your Cheffile. When
using Berkshelf, add the following to your Berksfile.

```ruby
cookbook 'windows', git: 'https://github.com/livinginthepast/windows-noop-cookbook.git'
```

