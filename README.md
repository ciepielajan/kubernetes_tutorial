# Kubernetes tutorial
https://helion.pl/ksiazki/kubernetes-kurs-video-wdrazanie-aplikacji-michal-zylowski,vuruap.htm






## 1. Wstęp

### 1.1. Przywitanie i omówienie kursu

### 1.2. O Kubernetesie w kilka minut

### 1.3. Środowisko potrzebne do pracy z kursem, cz. 1.

`Minikube`
autmat do uruchomienia napisany w GO (mac, windows, linux). Wspiera kilka systemów virtualizacji (np. KVM2, hyperkit, virtualbox). 
Aplikacja która po uruchomieniu utworzy nam Wirtualną maszynę i skonfigurują ją jako jednowęzłowy lokalnym klaster kubernetesa. 

Pobierz i zainstaluj:

Virtual Box

https://www.virtualbox.org/wiki/Linux_Downloads



### 1.4. Środowisko potrzebne do pracy z kursem, cz. 2.

Pobierz i zainstaluj:

Kubectl

https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/#install-kubectl-binary-with-curl-on-linux


Minikube

https://github.com/kubernetes/minikube
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

```

Uruchom Minikube
```
minikube start
```

Sprawdzić czy wszystkko przebiegło poprawnie
```
kubectl get nodes
```
![minikube_start](/src/img/minikube_start.png) 


### 1.5. Środowisko potrzebne do pracy z kursem, cz. 3.

Ponowne uruchomienie wirutalnej maszyny.

minikube  wykrywa wcześniej utworzoną VM i wykonuje restarting
```
minikube start
```




## 2. Podstawy interakcji z klastrem

### 2.1. Jak działa i czym jest kub



### 2.2. Pierwszy kontener

### 2.3. Definicje w plikach yaml

### 2.4. Wykonywanie poleceń w kontenerach

### 2.5. Pobieranie logów Poda

## 3. Obiekty w Kubernetesie

### 3.1. Pod, cz. 1.

### 3.2. Pod, cz. 2.

### 3.3. Pod, cz. 3.

### 3.4. ReplicationController/ReplicaSet i skalowanie, cz. 1.

### 3.5. ReplicationController/ReplicaSet i skalowanie, cz. 2.

### 3.6. ReplicationController/ReplicaSet i skalowanie, cz. 3.

### 3.7. Deployment i RollingUpdate, cz. 1.

### 3.8. Deployment i RollingUpdate, cz. 2.

### 3.9. Deployment i RollingUpdate, cz. 3.

### 3.10. Deployment i RollingUpdate, cz. 4.

### 3.11. Job

### 3.12. CronJob

### 3.13. Namespace

### 3.14. Pod: Zmienne środowiskowe

### 3.15. Pod: Volumeny

### 3.16. Secrets

## 4. Praca z aplikacją kubectl

### 4.1. Interakcja z obiektami

### 4.2. Kopiowanie plików pomiędzy kontenerem a maszyną lokalną

### 4.3. Informacje o klastrze

### 4.4. Autouzupełnianie

## 5. Uruchomienie klastra z kilkoma węzłami

### 5.1. Wstęp

### 5.2. Google Kubernetes Engine, cz. 1.

### 5.3. Google Kubernetes Engine, cz. 2.

### 5.4. Uruchomienie Kubernetesa na VPS za pomocą kubespray, cz. 1.

### 5.5. Uruchomienie Kubernetesa na VPS za pomocą kubespray, cz. 2.

### 5.6. Kubeadm na maszynach VirtualBox, cz. 1.

### 5.7. Kubeadm na maszynach VirtualBox, cz. 2.

### 5.8. Kubeadm na maszynach VirtualBox, cz. 3.

### 5.9. DaemonSet

## 6. Jak działa Kubernetes

### 6.1. Architektura rozwiązania

### 6.2. Namespace kube-system i analiza węzła master

### 6.3. Dostęp do ETCD

### 6.4. Pody statyczne

## 7. Kolejne funkcjonalności Kubernetesa

### 7.1. Etykiety i selektory

### 7.2. Kontenery init

### 7.3. Security context

### 7.4. Żądanie i limitowanie zasobów

## 8. Sieć na klastrze i wystawianie usług na zewnątrz

### 8.1. Przekierowanie portów

### 8.2. Łączenie usług wewnątrz klastra - obiekt Service

### 8.3. Wystawianie usług na zewnątrz

### 8.4. NodePort

### 8.5. LoadBalancer

## 9. Klaster z dodatkowymi narzędziami

### 9.1. Uruchomienie klastra z narzędziem helm oraz Ingress controllerem Nginx

### 9.2. Ingress, cz. 1.

### 9.3. Ingress, cz. 2.

### 9.4. Ingress, cz. 3.

### 9.5. Helm1

### 9.6. Cert-manager, cz. 1.

### 9.7. Cert-manager, cz. 2.

### 10. Przykłady końcowe

### 10.1. Uruchomienie narzędzia do skracania linków

### 10.2. Podłączenie klastra do projektów obliczeniowych
