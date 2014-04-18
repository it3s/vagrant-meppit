# Vagrant box for [Meppit](https://github.com/it3s/meppit)


## Setup

1. Install [Virtualbox](https://www.virtualbox.org/)
2. Install [Vagrant](http://www.vagrantup.com/)
3. Clone this repository `git clone https://github.com/it3s/vagrant-meppit.git`
4. Change to the directory `cd vagrant-meppit`
5. Create the instance `vagrant up`
6. Connect to the virtual machine `vagrant ssh`
7. Change to the meppit directory (inside the virtual machine) `cd meppit`
8. Start the development server (inside the virtual machine) `foreman start`
9. Open [localhost:3000](http://localhost:3000) in your browser


## Contributing

1. [Fork it](http://github.com/it3s/vagrant-meppit/fork)
2. Create your feature branch `git checkout -b my-new-feature`
3. Commit your changes `git commit -am 'Add some feature'`
4. Push to the branch `git push origin my-new-feature`
5. Create new Pull Request
