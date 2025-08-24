|Роль|Права роли|Группы пользователей|
|:----|:----|:----|
|ClusterAdmin|*|Head of Devops|
|ClusterSecurityAdmin|ConfigMaps, Secrets: *; \n ClusterRoles: *; Roles: *; Rolebindings: *; ClusterRoleBindings: *|Специалисты ИБ|
|NamespaceAdmin|Pods: *; Services: *; Deployments, StatefulSets: *; PersistentVolumes: *;|Devops|
|NamespaceReadAll|Pods: get, list, watch; Services: get, list, watch; Deployments, StatefulSets: get, list, watch; PersistentVolumes: get, list, watch;|Dev, Test, Эксплуатация|
|NamespaceRunner|Pods: get, list, watch, create, delete, update; Services: get, list, watch, create, delete, update; Deployments, StatefulSets: get, list, watch, create, delete, update; PersistentVolumes: get, list, watch, create, delete, update;|CD runners|
