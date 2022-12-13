Create a Ubuntu-based VM using Vagrant
steps
    # Have to given the path were the VM need to run
    # To intialize the box in the system need to give the command "Vagrant init" (required box name)
    # To start the box "Vagrant up" command have to use 
    # To connect with the virtual machine "Vagrant ssh" command to be used
    
 The main source of this vagrant and virtual machine is to run the multiple operating system in the excisting machine instead of buying new 
 
 
 
 
 G:\general softy\cmder
λ cd G:\ubuntutrusty64

G:\ubuntutrusty64
λ vagrant init ubuntu/trusty64
A `Vagrantfile` has been placed in this directory. You are now
ready to `vagrant up` your first virtual environment! Please read
the comments in the Vagrantfile as well as documentation on
`vagrantup.com` for more information on using Vagrant.

G:\ubuntutrusty64
λ vagrant up<img width="960" alt="2022-12-13" src="https://user-images.githubusercontent.com/118107382/207270333-dd813d1c-30a3-4d90-8f8f-f82b422183cb.png">
<img width="960" alt="2022-12-13" src="https://user-images.githubusercontent.com/118107382/207271109-741cb536-940c-4d93-bc8f-40221c6ffb01.png">

Bringing machine 'default' up with 'virtualbox' provider...
==> default: Importing base box 'ubuntu/trusty64'...
==> default: Matching MAC address for NAT networking...
==> default: Checking if box 'ubuntu/trusty64' version '20190514.0.0' is up to date...
==> default: Setting the name of the VM: ubuntutrusty64_default_1670920053472_15930
==> default: Clearing any previously set forwarded ports...
==> default: Clearing any previously set network interfaces...
==> default: Preparing network interfaces based on configuration...
    default: Adapter 1: nat
==> default: Forwarding ports...
    default: 22 (guest) => 2222 (host) (adapter 1)
==> default: Booting VM...
==> default: Waiting for machine to boot. This may take a few minutes...
    default: SSH address: 127.0.0.1:2222
    default: SSH username: vagrant
    default: SSH auth method: private key
    default: Warning: Connection reset. Retrying...
    default: Warning: Connection aborted. Retrying...
    default: Warning: Connection reset. Retrying...
    default:
    default: Vagrant insecure key detected. Vagrant will automatically replace
    default: this with a newly generated keypair for better security.
    default:
    default: Inserting generated public key within guest...
    default: Removing insecure key from the guest if it's present...
    default: Key inserted! Disconnecting and reconnecting using new SSH key...
==> default: Machine booted and ready!
==> default: Checking for guest additions in VM...
    default: The guest additions on this VM do not match the installed version of
    default: VirtualBox! In most cases this is fine, but in rare cases it can
    default: prevent things such as shared folders from working properly. If you see
    default: shared folder errors, please make sure the guest additions within the
    default: virtual machine match the version of VirtualBox you have installed on
    default: your host and reload your VM.
    default:
    default: Guest Additions Version: 4.3.40
    default: VirtualBox Version: 7.0
==> default: Mounting shared folders...
    default: /vagrant => G:/ubuntutrusty64

G:\ubuntutrusty64
λ notepad vagrantfile

G:\ubuntutrusty64
λ vagrant ssh
Welcome to Ubuntu 14.04.6 LTS (GNU/Linux 3.13.0-170-generic x86_64)

 * Documentation:  https://help.ubuntu.com/

 System information disabled due to load higher than 1.0

UA Infrastructure Extended Security Maintenance (ESM) is not enabled.

0 updates can be installed immediately.
0 of these updates are security updates.

Enable UA Infrastructure ESM to receive 64 additional security updates.
See https://ubuntu.com/advantage or run: sudo ua status

New release '16.04.7 LTS' available.
Run 'do-release-upgrade' to upgrade to it.


vagrant@vagrant-ubuntu-trusty-64:~$
    
