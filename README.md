# kubectl-ai-yaml-prompts
kubectl ai prompts testing


| NAME                   | PROMPT                                                                                              | DESCRIPTION                              | EXAMPLE                                                      |
|------------------------|-----------------------------------------------------------------------------------------------------|------------------------------------------|--------------------------------------------------------------|
| app-configmap          | Generate a Kubernetes ConfigMap for application configuration                                      | Creates a ConfigMap for storing app configs | [app-configmap.yaml](./yaml/app-configmap.yaml)                |
| app-job                | Generate a Kubernetes Job for running a batch process                                              | Creates a Job to run a batch process       | [app-job.yaml](./yaml/app-job.yaml)                            |
| app-multicontainer     | Generate a Kubernetes Pod with multiple containers                                                  | Creates a Pod that includes multiple containers | [app-multicontainer.yaml](./yaml/app-multicontainer.yaml)      |
| app-resources          | Generate a Kubernetes Deployment with resource limits and requests                                  | Creates a Deployment with resource constraints | [app-resources.yaml](./yaml/app-resources.yaml)                |
| app-secret             | Generate a Kubernetes Secret for storing sensitive information                                      | Creates a Secret for sensitive data       | [app-secret.yaml](./yaml/app-secret.yaml)                      |
| app                    | Generate a Kubernetes Deployment for an application                                                 | Creates a Deployment for an application  | [app.yaml](./yaml/app.yaml)                                    |
| app-cronjob            | Generate a Kubernetes CronJob for scheduled tasks                                                   | Creates a CronJob for scheduling tasks    | [app-cronjob.yaml](./yaml/app-cronjob.yaml)                    |
| app-livenessProbe      | Generate a Kubernetes Deployment with a liveness probe                                              | Creates a Deployment with liveness probe | [app-livenessProbe.yaml](./yaml/app-livenessProbe.yaml)        |
| app-readinessProbe     | Generate a Kubernetes Deployment with a readiness probe                                             | Creates a Deployment with readiness probe | [app-readnessProbe.yaml](./yaml/app-readnessProbe.yaml)        |
| app-secret-env         | Generate a Kubernetes Deployment that uses environment variables from a Secret                      | Creates a Deployment using Secret env variables | [app-secret-env.yaml](./yaml/app-secret-env.yaml)              |
| app-volumemounts       | Generate a Kubernetes Deployment with volume mounts                                                 | Creates a Deployment with volume mounts  | [app-volumemounts.yaml](./yaml/app-volumemounts.yaml)          |

