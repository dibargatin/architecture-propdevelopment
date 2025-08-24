## Инструкция

### 1. Запускаем Minikube

```bash
minikube start
```
### 2. Создаем пользователей

```bash
create-users.sh
```

### 3. Создаем роли

```bash
kubectl apply -f roles.yaml
```

### 4. Связываем пользователей с ролями

```bash
kubectl apply -f bindings.yaml
```