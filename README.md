# Windows Vagrant Box
This is the files for a Vagrant base box for Windows.

## Requirements

- Install Vagrant
- Install VirtualBox
- Install Vagrant plugins

```bash
vagrant plugin install winrm --plugin-version 1.8.1
vagrant plugin install winrm-fs
```

## Usage

1. Download the Vagrant box (private link) and save to `pathofexile.box`
2. Add box: `vagrant box add pathofexile.box --name SomeVM`
3. `vagrant init SomeVM`
4. `vagrant up`

