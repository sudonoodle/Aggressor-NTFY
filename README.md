# Aggressor-NTFY

A simple, headless aggressor script for red teams to receive beacon notifications.

![ntfy](https://github.com/user-attachments/assets/37900d94-71ae-4ee5-b4f8-3dfb9ceca869)

## Usage

1. Download the [ntfy](https://ntfy.sh) app (available for iOS, Android or web-based)
2. On the teamserver, execute the `Aggressor-NTFY.cna` script using the `agscript` utility:

```sh
./agscript [teamserver-ip] [teamserver-port] [NTFY] [password] Aggressor-NTFY.cna
./agscript 127.0.0.1 50050 NTFY s3cret Aggressor-NTFY.cna
```

3. Join the teamserver and view the randomly generated subscription string (or set your own)
4. Add the subsription to your ntfy app and test with the `/ntfy test` command in the event log.
