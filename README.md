# CSYE 6225 - Summer 2019



=======
## Team Information

| Name                | NEU ID      | Email Address             |

| Naqiyah Lakdawala	  | 001449938	  | lakdawala.n@husky.neu.edu |

| Saurabh Gujare      | 001424874   | gujare.s@husky.neu.edu    |

| Gaurao Thakur		    | 001417955   | thakur.ga@husky.neu.edu   |


Validate Template 
packer validate {name of the json file }


Build AMI
packer build {name od the json file}

Deployment
1. Launch EC2 instance from AWS console.
2. Access EC2 instance using CLI command ssh -i ~/.ssh/csye6225 centos@52.90.75.247
3. Install MySQL
4. Copy project war file to tomcat webapps directory
5. Run Tomcat Server
6. Access web app using http://ec2-52-90-75-247.compute-1.amazonaws.com:8080/{url}
