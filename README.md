# guix-discord

Add the following channel for access to the `discord` package.

```scheme
(channel
 (name 'guix-discord)
 (url "https://gitlab.com/jack-faller/guix-discord")
 (introduction
  (make-channel-introduction
   "78e9fecec8b671771153505323f3face650d478a"
   (openpgp-fingerprint
    "D97A 5464 A392 0366 1ED9  5C07 A043 7B42 9C10 4C61"))))
```
