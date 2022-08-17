# Parsec

## Problems

1. [When cloning a VM numerous times with Parsec pre-installed on it, I can only connect to a single VM through Parsec, as if they all have the same "ID".](#item_1)


## Answers

<a name="item_1"></a>
#### *When cloning a VM numerous times with Parsec pre-installed on it, I can only connect to a single VM through Parsec, as if they all have the same "ID".*

There is a unique ID that is created when Parsec is installed. Assuming Parsec was installed with the "shared" option to allow for it to start on startup, the configuration files can be found in "C:\ProgamData\Parsec".

1. Quit Parsec completely (it can't be running in the bottom right tray)
2. Delete the above directory
3. Restart Parsec

A new unique ID will be generated and you will need to log in again.