# Deployment-strategies
Recreate – Terminates all existing pods before creating new ones. Causes brief downtime. Good for dev/test environments.

Rolling Update – Gradually replaces old pods with new ones. Zero downtime. Ideal for production.

commands:-
kubectl apply -f recreate.yml

kubectl apply -f rolling.yml
