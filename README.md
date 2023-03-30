<h1>1. Installer Kind et Kubectl</h1>
Suivre cette documentation : https://kubernetes.io/docs/tasks/tools/
<h3>Install Kubectl</h3>
<code>curl.exe -LO "https://dl.k8s.io/release/v1.26.0/bin/windows/amd64/kubectl.exe"</code>
<h3>Install Kind</h3>
<code>curl.exe -Lo kind-windows-amd64.exe https://kind.sigs.k8s.io/dl/v0.17.0/kind-windows-amd64
>> Move-Item .\kind-windows-amd64.exe c:\Users\romai\kind.exe</code>
<h1>2. Pod Nginx</h1>
<h2>a. Héberger un premier Pod Nginx</h2>
<h2>b. A l’aide de la commande kubectl port-forward et d’un navigateur accéder à la page par défaut de votre pod Nginx</h2>
<h1>3. Connexion entre plusieurs Pods</h1>
<h2>a. A l’image du TP 1 sur Docker (question 7 et 8), héberger un Pod
phpmyadmin et mysql, cette fois-ci en utilisant minikube</h2>
<h2>b. Créer un service associé au Pod mysql</h2>
<h2>c. Connecter phpmyadmin avec le Service mysql et vérifier que vous pouvez
administrer cette base de données</h2>
<h2>d. Avec la commande kubectl-port forward, vérifier que phpmyadmin arrive à
contacter et administrer votre base de données mysql</h2>
<h2>e. Ajouter un Ingress pour accéder à phpmyadmin sans utiliser la commande
kubectl port-forward</h2>
