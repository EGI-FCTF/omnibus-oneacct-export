source 'https://api.berkshelf.com'

# The apt cookbook is required to bring the apt cache up-to-date on Ubuntu
# systems, since the cache can become stale on older boxes.
cookbook 'apt', '~> 2.0'

cookbook 'omnibus'

cookbook 'omnibus-build', path: 'cookbooks/omnibus-build'
cookbook 'centos5-atrpms-repository', path: 'cookbooks/centos5-atrpms-repository'
cookbook 'resolver'

# Uncomment to use the latest version of the Omnibus cookbook from GitHub
#cookbook 'omnibus', github: 'opscode-cookbooks/omnibus'
