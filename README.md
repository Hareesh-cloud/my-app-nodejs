# my-app-nodejs

replicaCount: 1

image:
  repository: gcr.io/project_name/image_name
  tag: latest
  pullPolicy: Always

service:
  type: LoadBalancer
  port: 3000
