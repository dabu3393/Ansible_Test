# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
    config.vm.box = "geerlingguy/centos7"

    config.ssh.insert_key = false

    config.vm.synced_folder ".", "/vagrant", disabled: true
  

    # App server 1
    config.vm.define "app1" do |app|
        app.vm.hostname = "Server-1.test"
        app.vm.network :private_network, ip: "192.168.60.4"
    end 
  
    # App server 2
    config.vm.define "app2" do |app|
        app.vm.hostname = "Server-2.test"
        app.vm.network :private_network, ip: "192.168.60.5"
    end

    # App server 3
    config.vm.define "app3" do |app|
        app.vm.hostname = "Server-3.test"
        app.vm.network :private_network, ip: "192.168.60.6"
    end

    # App server 4
    config.vm.define "app4" do |app|
        app.vm.hostname = "Server-4.test"
        app.vm.network :private_network, ip: "192.168.60.7"
    end

    # App server 5
    config.vm.define "app5" do |app|
        app.vm.hostname = "Server-5.test"
        app.vm.network :private_network, ip: "192.168.60.8"
    end

    # App server 6
    config.vm.define "app6" do |app|
        app.vm.hostname = "Server-6.test"
        app.vm.network :private_network, ip: "192.168.60.9"
    end

end