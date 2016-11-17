## cloud.gov deployment for the notifications application

This is just a [concourse.ci](https://concourse.ci/) pipeline for the deployment of [cf notifications](https://github.com/cloudfoundry-incubator/notifications).


To fly the pipeline:

```
fly -t ci set-pipeline -p deploy-notifications -c pipeline.yml -l credentials.yml
```