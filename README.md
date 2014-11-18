k8s_gitlab
==========

#Requirements
- mysql server/container

Create the database and necessary user
```
CREATE USER 'gitlab'@'%.%.%.%' IDENTIFIED BY 'password';
CREATE DATABASE IF NOT EXISTS `gitlabhq_production` DEFAULT CHARACTER SET `utf8` COLLATE `utf8_unicode_ci`;
GRANT ALL PRIVILEGES ON `gitlabhq_production`.* TO 'gitlab'@'%.%.%.%';
```

#Usage
1st, launch the redis-gitlab service
```

```

Then, launch the gitlab replication controller
```

```

default credentials:
root
5iveL!fe

