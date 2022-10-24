# Composite update site example

This repo contains the example config for creating a composite update site with
tycho, and group extension in categories.

## 1. Define source repositories

Edit the `pom.xml` file, adding a `repository` block for each source repository
containing the extensions you want to provide here.

## 2. Categorizing features

Edit the `category.xml` file, creating categories and adding features to them.

## 3. Build update site

Run `mvn package` to create the update site.