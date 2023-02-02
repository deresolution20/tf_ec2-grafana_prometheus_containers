# tf_ec2-grafana_prometheus_containers

<h2>Deploy a docker stack on ec2 with Grafana and Prometheus</h2>

<b> steps to deploy<b/>

Download the files and place in directory
Run:
``` 
Terraform init 
```
once complete, run:
```
Terraform apply
```

it will output the IP for Grafana at port 3000 and Prometheus at port 9090
wait for the ec2 instance to finish and when both checks passed, you can log in and set up your dashboard using prometheus as the data source


![Screenshot from 2023-02-01 17-04-27](https://user-images.githubusercontent.com/85902399/216198847-9286f9bc-08e4-48d2-b7a0-dfa29b2bd398.png)


![Screenshot from 2023-02-01 17-05-17](https://user-images.githubusercontent.com/85902399/216198865-f4dfb619-9af4-4f47-938a-60b63e2e133d.png)


![Screenshot from 2023-02-01 17-07-41](https://user-images.githubusercontent.com/85902399/216198882-1fd2f594-7335-41c8-afab-07dfec34b087.png)

![Screenshot from 2023-02-01 17-09-10](https://user-images.githubusercontent.com/85902399/216198900-9355410f-29eb-4e2d-a4b8-d7d615eb3a08.png)


