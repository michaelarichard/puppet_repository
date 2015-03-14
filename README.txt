#
#
#

1. Edit the configure_r10k.pp file to point to your puppet repository. 

cat configure_r10k.pp| grep remote
      'remote'  => 'https://github.com/michaelarichard/puppet_repository.git',

2. Install required dependancy modules from puppetforge
puppet module install zack-r10k
