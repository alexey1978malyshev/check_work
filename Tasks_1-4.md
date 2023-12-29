## Task 1
mkdir check_work    
cd ~/check_work   
cat > pet_animals    
cat > pack_animals    
cat pet_animals  pack_animals > animals    
cat animals    
mv animals humans_friends    
ls -alih    

## Task 2
cd ..    
mkdir check_work_1    
cd ~/check_work    
mv humans_friends  ~/check_work_1  
cd ~/check_work_1    
ls -alih    

## Task 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server    

## Task 4
sudo wget https://download.docker.com/linux/ubuntu/dists/lunar/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-lunar_amd64.deb    
sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-lunar_amd64.deb    
sudo dpkg -r docker-ce-cli    
