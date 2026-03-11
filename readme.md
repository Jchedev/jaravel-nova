Nova Improvements

Install

- Change guard by default

- Run install command

Fix to do :

Align-items:enter on the td of detail

Make changes (from another Project) :

1. Rename public/vendor/nova to nova-old

2. ln -s ../../vendor/jchedev/jaravel-nova/public/ public/vendor/nova (from root)

3. Go in /vendor/jchedev/jaravel-nova
    - npm install
    - npm run watch

3. Copy changes on other repo and commit

4. Remember to yarn prod and commit

4. On projects, run composer update jchedev/jaravel-nova