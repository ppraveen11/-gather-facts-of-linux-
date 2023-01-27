# gather-facts-of-linux

This playbook runs on all hosts, and uses the command module to run the df -h, free -m, and netstat -s commands, which gather information on disk usage, memory usage, and network statistics respectively. The output of each command is registered in a variable, and then printed using the debug module.
You can access the information using the variable and use it in your further tasks.


![root@local__ansiblews 1_27_2023 5_06_23 PM](https://user-images.githubusercontent.com/56449458/215080543-eef1c1b6-f0a7-43d5-a5f4-214f0c060dad.png)
![root@local__ansiblews 1_27_2023 5_23_36 PM](https://user-images.githubusercontent.com/56449458/215080514-06e3c187-4dc7-4797-9ec8-37d102f50a10.png)
![root@local__ansiblews 1_27_2023 5_23_56 PM](https://user-images.githubusercontent.com/56449458/215080605-da7727f1-0956-423c-b0eb-0a5eaebc9d18.png)
