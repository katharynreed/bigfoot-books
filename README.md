# Bigfoot Books

Have you ever felt like you just don't exist? We understand how that feels! Here at Bigfoot Books we aim to make sure that no one is hunted for being different. Located deep in the forests of Oregon (or Washington, depending on who you ask), we provide a blanket of cover for all book loving types. Even the ones with really, really, really big feet.

## Prerequisites

You will need one of the following server management programs properly installed on your computer.

* [MAMP](https://www.mamp.info/en/)
* [WAMP](http://www.wampserver.com/en/)
* [LAMP](https://www.apachefriends.org/index.html)

## Installation

**Step 1**: Clone this repository to your local computer

```console
git clone https://github.com/katharynreed/bigfoot-books
```

**Step 2**: Using your server management software, import the `bookstore.sql.zip` file from `/sites/db-backup`

**Step 3**: Create a new user on the database using username: 'bookstore' and password: 'bookstore'; you can double check in sites/default/settings.php

**Step 4**: Ensure that your web server software's document root is set to the project's root directory and that the MySQL port is set to 8889

**Step 5**: Visit the app at [http://localhost:8889](http://localhost:8889).

## License

MIT License. Copyright 2017 Katie Reed
