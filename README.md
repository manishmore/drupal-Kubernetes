# drupal-Kubernetes
Kubernetes deploying an instance of Drupal 

$cd drupal-Kubernetes && ls -al

-rw-r--r--   1 manish  staff  1194 Dec  3 00:18 drupal-postgres.yaml

-rw-r--r--   1 manish  staff  1222 Dec  3 00:17 drupal.yaml

-rw-r--r--   1 manish  staff   747 Dec  3 00:16 local-v.yaml

# run the individual commands listed in it:

kubectl create -f drupal-postgres.yaml

kubectl create -f drupal.yaml

kubectl create -f drupal.yaml

If you are running in Minikube, run the following:

$ minikube service drupal --url

Access the newly deployed Drupal site via http://<IP_ADDRESS>:30080

Send an Issue, a pull request or knock me at Twitter: <a href="https://twitter.com/moremanish">@moremanish</a>
