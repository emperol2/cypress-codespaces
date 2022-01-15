# Cypress Codespaces Example 👨‍💻

This is an example Cypress project running on Codespaces with an ability to run `cypress open` on `X11`.

# How to use 🤔

1. Git clone this project
2. Open this project on Codespaces
3. On Codespaces (first time) run time command below to install the dependencies:

```
npm install
```

4. To open the Remote Client on X11, visit below link in your browser and the password is `MUST_BE_SOMETHING`:

```
http://127.0.0.1:8080
```

5. To open the Cypress UI Test Runner:

```
npx cypress open
```

# Screenshot 🏞

# Trobleshooting 🔧

If there is the problem with Cypress version below:

```
No version of Cypress is installed in: /root/.cache/Cypress/9.2.1/Cypress

Please reinstall Cypress by running: cypress install
```

Run this command to fix it:

```
npx cypress install --force
```

# Ignore 🙅‍♂️

You can safely ignore the dbus error if your tests are executing fine see mentioned [here](https://github.com/cypress-io/cypress/issues/4925).

```
[3555:0115/164125.919187:ERROR:bus.cc(392)] Failed to connect to the bus: Failed to connect to socket /run/dbus/system_bus_socket: No such file or directory
[3555:0115/164125.924596:ERROR:bus.cc(392)] Failed to connect to the bus: Could not parse server address: Unknown address type (examples of valid types are "tcp" and on UNIX "unix")
[3555:0115/164125.924639:ERROR:bus.cc(392)] Failed to connect to the bus: Could not parse server address: Unknown address type (examples of valid types are "tcp" and on UNIX "unix")
```

# Thanks 🙏🏼

For your reference:

https://github.com/cypress-io/cypress-documentation/issues/2956#issuecomment-930527836

https://github.com/AriPerkkio/cypress-codespaces-example
