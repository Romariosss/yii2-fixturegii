Yii2-fixture/template-generator
======================
quick way generate fixture templates for all tables based on table schema, or fixtures data based on tables data
Ability to set multiple tables with mask

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require-dev --prefer-dist insolita/yii2-fixturegii "*"
```

or add

```
"insolita/yii2-fixturegii": "*"
```

to the require-dev section of your `composer.json` file.


Usage
-----

Go to gii, choose FixtureTemplateGenerator, set needed tables or "*" for all, go to setted templatePath,
correct as you want and run php console/yii fixture/generate-all
