# ho's-world

``` bash
git clone https://github.com/k8s-ho/my_world
cd my_world
```

<br>

### Usage

1. Move your key pair file into the "my_world" directory
<img width="731" alt="abc" src="https://github.com/k8s-ho/my_world/assets/118821939/d4f608ed-25f1-4306-8ecb-e773f098555b">

2. change the default value of the "key_name" variable in "main.tf" to your key pair name.
![ccc](https://github.com/k8s-ho/my_world/assets/118821939/382eb832-fa80-4bdf-abae-ce547b8b09a5)



``` bash
chmod 600 *.pem # chmod 600 [your key pair file]
terraform init
terraform apply
```
<br>

### tear down
```bash
terraform destroy
```
