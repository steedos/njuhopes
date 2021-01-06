<h1 align="center">
  NJU Hopes Funds
</h1>

<p align="center" style="border-top: solid 1px #cccccc">
NJU Hopes Funds
</p>

<h3 align="center">
 🤖 🎨 🚀
</h3>

### About Steedos

[Steedos Platform](https://github.com/steedos/steedos-platform) is an open source alternative to salesforce low code development platform. You can easily create intelligent and mobile enterprise applications by clicking the mouse.

## Requirements

- [MongoDB](https://www.mongodb.com/try/download/) version >= 3.4. MongoDB is a general purpose, document-based, distributed database built for modern application developers and for the cloud era.
- [Node.js](https://nodejs.org/en/download/) version >= 10.15.1 or above (which can be checked by running `node -v`). You can use [nvm](https://github.com/nvm-sh/nvm) for managing multiple Node versions on a single machine installed.

## Project Structure

```sh
njuhopes
├── steedos-app/main/default
│   ├── applications
│   │   └── okr.app.yml
│   └── objects
│       └──okr__c
│           ├── buttons
│           │   └── print.button.yml
│           │   └── print.button.js
│           ├── fields
│           │   └── name.field.yml
│           │   └── description.field.yml
│           │   └── isDone.field.yml
│           │   └── status__c.field
│           │   └── ...
│           ├── listviews
│           │   └── all.listview.yml
│           │   └── recent.listview.yml
│           │   └── my.listview.yml
│           ├── permissions
│           │   └── user.permission.yml
│           │   └── admin.permission.yml
│           │   └── okr_manager.permission.yml
│           └── okr.object.yml
│           └──...
├── .env
├── .gitignore
├── package.json
├── README.md
├── server.js
├── steedos-config.yml
└── yarn.lock
```

##  Quick Start

The source code of the project depends on nodejs environment. To use mongodb database, the corresponding running environment should be deployed first.

  1. Start the database  
  2. Install dependent packages
  3. Running project
  4. Using browser access `http://127.0.0.1:5000/`    For the first time, the database is empty. You need to register an account and choose to create an enterprise.

## Keep in Contact

If you have any questions or want to talk to other users of Steedos Platform , please jump to GitHub for discussion [Click to Discuss](https://github.com/steedos/steedos-platform/discussions) or [Join me on Slack-it's a faster,simpler way to work](https://join.slack.com/t/steedos/shared_invite/zt-jq7eupr9-cgKrUOyWb1zymniRzhH4jg).
