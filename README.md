## Pineline status
[![CircleCI](https://circleci.com/gh/kien-ndt/udacity-project5_udacity_aws_devops.svg?style=svg)]

## Deploy project3's backend in k8s
1. Build and test backend.
2. Lint dockerfile.
3. Create new dockerimage for backend and push to dockerhub.
4. Deploy dockerimage to k8s as green version. When fail, remove dockerfile in dockerhub.
5. Smoke test green version. When fail, remove dockerfile in dockerhub, delete green version in k8s.
6. Update service port point to green version.
7. Delete old blue version.