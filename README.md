# CMPE 172 - Lab #10 Notes

## CI Workflow Part 1

Below screenshot shows where we get workflow templates from

![Actions](images/workflows.png)

Below screenshot shows the success for the first workflow (build).

![First Workflow](images/gradle-workflow.png)

## CI Workflow Part 2

See below for Service Accounts.

![Service accounts](images/service-accounts.png)

Below image shows a key for the service account.

![Key](images/json-key.png)

Below image shows Action Secrets on GitHub.

![Action Secrets](images/secrets.png)

Below image shows the cluster on GKE.

![Cluster](images/cluster.png)

Below image shows the releases I created.

![Releases](images/release.png)

Below image shows all the workflows seen on GitHub.

![All Workflows](images/all-workflows.png)

Below image shows the details on the successful release for GKE deployment.

![Deployment](images/gke-workflow.png)

Below image shows the workload (pods) on GKE.

![Pods](images/pods.png)

Below image shows the service on GKE.

![Service](images/service.png)

Below image shows the process of creating the ingress.

![Ingress](images/create-ingress.png)

Below image shows the completely created ingress on GKE.

![Created Ingress](images/ingress-complete.png)

The below image shows the gumball webpage being served by GKE.

![Web Gumball](images/gumball-web.png)

The main challenge I faced was trying to create the secret keys on GitHub. I mostly wasn't sure about what to put for GKE_PROJECT but after looking online, I found out that I needed to put the project ID and not the project name.