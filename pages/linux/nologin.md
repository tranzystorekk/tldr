# nologin

> Alternative shell that prevents a user from logging in.
> More information: <https://manned.org/nologin.5>.

- Set a user's login shell to `nologin` to prevent the user from logging in:

`chsh {{[-s|--shell]}} {{user}} nologin`

- Customize message for users with the login shell of `nologin`:

`echo "{{declined_login_message}}" > /etc/nologin.txt`
