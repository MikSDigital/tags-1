Symfony Standard Edition v.3.4.4
================================


What's inside?
--------------

Attempt to craete tag system, following https://www.youtube.com/watch?v=_XJOT9C-Wa0 tutorial:

  1) generate entity Post: ```bin/console doctrine:generate:entity```
  2) generate CRUD for this entity: ```bin/console doctrine:generate:crud```
  3) apply changing schema for DB : ```bin/console doctrine:schema:update --force```
  4) generate entity Tag: ```bin/console doctrine:generate:entity```
  5) ```bin/console doctrine:generate:entities AppBundle```  ENTITIES (!!!)


