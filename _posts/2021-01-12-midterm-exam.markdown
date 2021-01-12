---
layout: post
categories: jekyll update
title:  "MIDTERM EXAM: Hands-On"
---
![ME](https://user-images.githubusercontent.com/75419236/104274719-7658c700-54dc-11eb-99fc-8fb5d5beaffa.png)
1. Fork this repository [https://github.com/ajcanlas-tip/sysad2-12021.git](https://github.com/ajcanlas-tip/sysad2-12021.git)

2. Clone your new repository in your VM *https://github.com/< your username >/sysad2-12021.git*

3. Create a branch named "midterm-exam" and checkout in that branch.

4. Create an Ansible playbook that does the following with an input of a config.yaml file and arranged Inventory file:

	 4.1 Install and configure Elastic Stack in separate  hosts (Elastic Search, Kibana, Logstash)

	 4.2 Install Nagios in one host

	 4.3 Install Grafana,Prometheus and Influxdb in seperate hosts (Influxdb,Grafana,Prometheus)

	 4.4 Install Lamp Stack in seperate hosts (Httpd + Php,Mariadb)

5. push and commit your midterm-exam branch in the VM (no need for ansible.cfg upon pushing)

6. request a pull request from that branch in GitHub

7. For your midterm exam to be counted, please paste your repository link as an answer in this exam.  

### OUTPUT:
Github: [https://github.com/qrjhjimenez/sysad2-12021/tree/midterm-exam](https://github.com/qrjhjimenez/sysad2-12021/tree/midterm-exam])  
`├── 1811243`  
`│   └── midterm-exam`  
`│       ├── 02-beats-input.conf`  
`│       ├── 10-syslog-filter.conf`  
`│       ├── 30-elasticsearch-output.conf`  
`│       ├── config.yaml`  
`│       ├── grafana_nginx`  
`│       ├── index.html`  
`│       ├── inventorymid`  
`│       ├── kibana_config`  
`│       ├── midterm.yml`  
`│       ├── prometheus_config`  
`│       ├── prometheus_service`  
`│       ├── README.md`  
`│       └── roles`  
`│           ├── apache`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── elasticsearch`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── grafana`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── influxdb`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│          │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── kibana`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── logstash`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── mariadb`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           ├── nagios`  
`│           │   ├── defaults`  
`│           │   │   └── main.yml`  
`│           │   ├── handlers`  
`│           │   │   └── main.yml`  
`│           │   ├── meta`  
`│           │   │   └── main.yml`  
`│           │   ├── README.md`  
`│           │   ├── tasks`  
`│           │   │   └── main.yml`  
`│           │   ├── tests`  
`│           │   │   ├── inventory`  
`│           │   │   └── test.yml`  
`│           │   └── vars`  
`│           │       └── main.yml`  
`│           └── prometheus`  
`│               ├── defaults`  
`│               │   └── main.yml`  
`│               ├── handlers`  
`│               │   └── main.yml`  
`│               ├── meta`  
`│               │   └── main.yml`  
`│               ├── README.md`  
`│               ├── tasks`  
`│               │   └── main.yml`  
`│               ├── tests`  
`│               │   ├── inventory`  
`│               │   └── test.yml`  
`│               └── vars`  
`│                   └── main.yml`  
`└── README.md`
~
~
~
~
~
~
~
~
-- INSERT --                                                                                  
