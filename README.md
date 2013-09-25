# Drupal 7 on OpenShift

### Git commands

This repo was created with the following commands:

```
git remote add -f drupal http://git.drupal.org/project/drupal.git
git subtree add --prefix php drupal 7.23 --squash
```

When a new Drupal version (like 7.24) comes out, you should be able to upgrade it with the following command:

```
git remote add -f drupal http://git.drupal.org/project/drupal.git
git subtree add --prefix php drupal 7.24 --squash
```

