# OverTheWire Bandit – Level 0

## Objective

The objective of Level 0 is to connect to the Bandit server using SSH.

## Command

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

## Explanation

* `ssh` → Used to securely connect to a remote server.
* `bandit0` → Username used to log in.
* `@` → Separates the username and server address.
* `bandit.labs.overthewire.org` → Server hostname.
* `-p` → Specifies the port number.
* `2220` → Port used by the Bandit server.

## Password

```text
bandit0
```

After entering the password, press **Enter**.

## Successful Login

After successful login, the terminal shows:

```bash
bandit0@bandit:~$
```

This means we are successfully logged in to the Bandit server as the `bandit0` user.
