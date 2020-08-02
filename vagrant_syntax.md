### Creating a vagrantfile 
i.
 ```bash 
mkdir vagrantfiletest
   ```
ii.
```bash 
cd vagrantfiletest
```
iii.
```bash
vagrant init
```

### Creating a basic vagrantfile structure 
```bash
vagrant init --minimal
or 
vagrant init -m
```
This will give the following basic structure:
```bash
Vagrant.configure("2") do |config| 
config.vm.box = "base"
end
```