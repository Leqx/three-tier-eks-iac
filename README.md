<a name="readme-top"></a>

<div align="center">

  <h1>Three-tier eks iac</h1>

<!-- Badges -->
<p>
  <a href="https://github.com/Leqx/three-tier-eks-iac/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/Leqx/three-tier-eks-iac" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/Leqx/three-tier-eks-iac" alt="last update" />
  </a>
  <a href="https://github.com/Leqx/three-tier-eks-iac/network/members">
    <img src="https://img.shields.io/github/forks/Leqx/three-tier-eks-iac" alt="forks" />
  </a>
  <a href="https://github.com/Leqx/three-tier-eks-iac/stargazers">
    <img src="https://img.shields.io/github/stars/Leqx/three-tier-eks-iac" alt="stars" />
  </a>
  <a href="https://github.com/Leqx/three-tier-eks-iac/issues/">
    <img src="https://img.shields.io/github/issues/Leqx/three-tier-eks-iac" alt="open issues" />
  </a>
  <a href="https://github.com/Leqx/three-tier-eks-iac/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/Leqx/three-tier-eks-iac.svg" alt="license" />
  </a>
</p>
   
<h4>
    <a href="https://github.com/Leqx/three-tier-eks-iac/">View Demo</a>
  <span> · </span>
    <a href="https://github.com/Leqx/three-tier-eks-iac">Documentation</a>
  <span> · </span>
    <a href="https://github.com/Leqx/three-tier-eks-iac/issues/">Report Bug</a>
  <span> · </span>
    <a href="https://github.com/Leqx/three-tier-eks-iac/issues/">Request Feature</a>
  </h4>
</div>

<br />

> This a three tier microservice TODO List application project. It's meant to showcase my understanding of devsecops by utilizing terraform, aws and k8s.

<br />

<!-- Table of Contents -->

# :notebook_with_decorative_cover: Table of Contents

- [:notebook_with_decorative_cover: Table of Contents](#notebook_with_decorative_cover-table-of-contents)
  - [:star2: About the Project](#star2-about-the-project)
    - [:space_invader: Tech Stack](#space_invader-tech-stack)
    - [:dart: Features](#dart-features)
  - [:toolbox: Getting Started](#toolbox-getting-started)
    - [:bangbang: Prerequisites](#bangbang-prerequisites)
    - [:gear: Installation](#gear-installation)
      - [:small_blue_diamond: Build Docker image](#small_blue_diamond-build-docker-image)
      - [:small_blue_diamond: MongoDB Database Setup](#small_blue_diamond-mongodb-database-setup)
      - [:small_blue_diamond: Backend API Setup](#small_blue_diamond-backend-api-setup)
      - [:small_blue_diamond: Frontend Client Setup](#small_blue_diamond-frontend-client-setup)
      - [:small_orange_diamond: Any issue with the pods ? check logs](#small_orange_diamond-any-issue-with-the-pods--check-logs)
      - [:small_blue_diamond: Monitoring Setup](#small_blue_diamond-monitoring-setup)
      - [:small_blue_diamond: Destroy Kubernetes Resources and Cluster](#small_blue_diamond-destroy-kubernetes-resources-and-cluster)
  - [:compass: Roadmap](#compass-roadmap)
  - [:wave: Contributing](#wave-contributing)
  - [:warning: License](#warning-license)
  - [:handshake: Contact](#handshake-contact)
  - [:gem: Acknowledgements](#gem-acknowledgements)

<!-- About the Project -->

## :star2: About the Project

<div align="center"> 
    <h6>System Architecture Diagram</h6>
  <img src="readme-assets/screenshot.png"    alt="screenshot" />

  <br/>
  <h6>Frontend UI</h6>
  <img src="readme-assets/screenshot.png"    alt="screenshot" />
</div>

<!-- TechStack -->

### :space_invader: Tech Stack

<details>
<summary>Languages</summary>
    <a href="https://www.w3schools.com/js/">
     <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="javascript" />
    </a> <br/> 
</details>

<details>
<summary>Client</summary>
    <a href="https://react.dev/">
     <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="reactjs" />
    </a> 
</details>

<details>
<summary>Server</summary>
    <a href="https://nodejs.org/">
     <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="nodejs" />
    </a> 
    <a href="https://expressjs.com">
     <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="expressjs" />
    </a>
</details>

<details>
<summary>Database</summary>
    <a href="https://mongodb.com/">
     <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" alt="mongodb" />
    </a> 
</details>

<details>
<summary>Devops</summary>
    <a href="https://git-scm.com/">
     <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" alt="git" />
    </a> 
     <a href="https://terraform.io/">
     <img src="https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white" alt="terraform" />
    </a>
    <a href="https://docker.com/">
     <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" alt="docker" />
    </a> 
    <a href="https://kubernetes.io/">
     <img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white" alt="kubernetes" />
    </a>
    <a href="https://grafana.com/">
     <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white" alt="grafana" />
    </a> 
    <a href="https://prometheus.io/">
     <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white" alt="prometheus" />
    </a>   
</details>

<details>
<summary>Cloud</summary> 
    <a href="https://aws.amazon.com/">
     <img src="https://img.shields.io/badge/Amazon_AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="aws" />
    </a> 
</details>

<!-- Features -->

### :dart: Features

- Create TODOs
- Read TODOs
- Update TODOs
- Delete TODOs

<!-- Getting Started -->

## :toolbox: Getting Started

<!-- Prerequisites -->

### :bangbang: Prerequisites

**Install Kubectl**
https://kubernetes.io/docs/tasks/tools/

**Install Helm**
https://helm.sh/docs/intro/install/

```bash
helm repo update
```

<!-- Installation -->

### :gear: Installation

**Install/update latest AWS CLI:** (make sure install v2 only)
https://aws.amazon.com/cli/

**Update the Kubernetes context:**

```bash
aws eks update-kubeconfig --name my-eks-cluster --region us-west-2
```

**Verify access:**

```bash
kubectl auth can-i "*" "*"
kubectl get nodes
```

**Verify autoscaler running:**

```bash
kubectl get pods -n kube-system
```

**Check Autoscaler logs:**

```bash
kubectl logs -f \
  -n kube-system \
  -l app=cluster-autoscaler
```

**Check load balancer logs:**

```bash
kubectl logs -f -n kube-system \
  -l app.kubernetes.io/name=aws-load-balancer-controller
```

#### :small_blue_diamond: Build Docker image

**For Mac:**

```bash
export DOCKER_CLI_EXPERIMENTAL=enabled
aws ecr-public get-login-password --region us-east-1 | docker login --username AWS --password-stdin public.ecr.aws/w8u5e4v2
```

Build Front End :

```bash
docker buildx build --platform linux/amd64 -t workshop-frontend:v1 .
docker tag workshop-frontend:v1 public.ecr.aws/w8u5e4v2/workshop-frontend:v1
docker push public.ecr.aws/w8u5e4v2/workshop-frontend:v1
```

Build Back End :

```bash
docker buildx build --platform linux/amd64 -t workshop-backend:v1 .
docker tag workshop-backend:v1 public.ecr.aws/w8u5e4v2/workshop-backend:v1
docker push public.ecr.aws/w8u5e4v2/workshop-backend:v1
```

**For Linux/Windows:**

Build Front End :

```bash
docker build -t workshop-frontend:v1 .
docker tag workshop-frontend:v1 public.ecr.aws/w8u5e4v2/workshop-frontend:v1
docker push public.ecr.aws/w8u5e4v2/workshop-frontend:v1
```

Build Back End :

```bash
docker build -t workshop-backend:v1 .
docker tag workshop-backend:v1 public.ecr.aws/w8u5e4v2/workshop-backend:v1
docker push public.ecr.aws/w8u5e4v2/workshop-backend:v1
```

**Update Kubeconfig**
Syntax: aws eks update-kubeconfig --region region-code --name your-cluster-name

```bash
aws eks update-kubeconfig --region us-west-2 --name my-eks-cluster
```

**Create Namespace**

```bash
kubectl create ns workshop

kubectl config set-context --current --namespace workshop
```

#### :small_blue_diamond: MongoDB Database Setup

**To create MongoDB Resources**

```bash
cd k8s_manifests/mongo_v1
kubectl apply -f secrets.yaml
kubectl apply -f deploy.yaml
kubectl apply -f service.yaml
```

#### :small_blue_diamond: Backend API Setup

Create NodeJs API deployment by running the following command:

```bash
kubectl apply -f backend-deployment.yaml
kubectl apply -f backend-service.yaml
```

#### :small_blue_diamond: Frontend Client Setup

Create the Frontend  resource. In the terminal run the following command:

```bash
kubectl apply -f frontend-deployment.yaml
kubectl apply -f frontend-service.yaml
```

Finally create the final load balancer to allow internet traffic:

```bash
kubectl apply -f full_stack_lb.yaml
```

#### :small_orange_diamond: Any issue with the pods ? check logs

```bash
kubectl logs -f POD_ID -f
```

#### :small_blue_diamond: Monitoring Setup

**Verify Services**

```bash
kubectl get svc -n prometheus
```

**edit the Prometheus-grafana service:**

```bash
kubectl edit svc prometheus-grafana -n prometheus
```

**change ‘type: ClusterIP’ to 'LoadBalancer'**

Username: admin
Password: prom-operator

Import Dashboard ID: 1860

Exlore more at: https://grafana.com/grafana/dashboards/

#### :small_blue_diamond: Destroy Kubernetes Resources and Cluster

```bash
cd ./k8s_manifests
kubectl delete -f -f
```

**Remove AWS Resources to stop billing**

```bash
cd terraform
terraform destroy --auto-approve
```

<!-- Roadmap -->

## :compass: Roadmap

- [ ] Add CI Server
  - [ ] Jenkins
  - [ ] SonarQube
  - [ ] Trivy
  - [ ] OWASP
- [ ] Add CD Capabilities
  - [ ] ArgoCD
  - [ ] Argo Events
  - [ ] Argo Workflows
  - [ ] Argo Rollouts
- [ ] Add Service Mesh
  - [ ] Istio

<!-- Contributing -->

## :wave: Contributing

<a href="https://github.com/Leqx/three-tier-eks-iac/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Leqx/three-tier-eks-iac" />
</a>

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- License -->

## :warning: License

Distributed under the no License. See LICENSE.txt for more information.

<!-- Contact -->

## :handshake: Contact

Eugene Alex - [@twitter_handle](https://twitter.com/twitter_handle) - email@email_client.com

Project Link: [https://github.com/Leqx/three-tier-eks-iac](https://github.com/Leqx/three-tier-eks-iac)

<a href="https://www.linkedin.com/in/eugene-alex-1890a1195/">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="linkedin" />
</a>
<a href="https://x.com">
 <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="twitter" />
</a>
<a href="https://google.com">
 <img src="https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white" alt="website" />
</a>
<a href="https:whatsapp.com/">
 <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="whatsapp" />
</a>

<!-- Acknowledgments -->

## :gem: Acknowledgements

I would like to acknowledge the following developers,please follow them and star there work:

- [Understanding EKS](https://www.youtube.com/@learnTechWithSandip)
- [Understanding Terraform](https://www.youtube.com/@cloudchamp/)
