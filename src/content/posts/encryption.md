---
title: Encryption Example
published: 2020-02-02
updated: 2026-05-28
description: "Password: 123456"
tags:
  - Encryption
draft: false
---
# Password Protected Post

This is an example of a password-protected post in the Twilight theme. The content below is encrypted using AES and can only be viewed by entering the correct password.

## Frontmatter Example

```yaml
---
title: Encryption Example
published: 2020-02-02
encrypted: true
password: "your-password"
...
---
```

- `encrypted` - Whether encryption is enabled for the post.
- `password` - The password required to unlock the content.

## Note

:::warning  
Do not use this for extremely sensitive information like bank passwords or private keys. The encryption happens on the client side, and the password itself is stored in the post's metadata (though usually not displayed directly).  
:::

我去