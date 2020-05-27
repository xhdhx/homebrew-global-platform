# Homebrew Tap for GlobalPlatform and GPShell

Forked from [DylanSchell/homebrew-personal](https://github.com/DylanSchell/homebrew-personal). Only update package digest method from sha1 to sha256.

## Useage

```
brew tap hui-742369/globalplatform
brew update
brew install globalplatform
```

or

```
brew tap hui-742369/globalplatform
brew update
brew install gpshell
```

## Requirement

1. Use brew to install libressl

  ```
  brew install libressl
  ```

2. Link libressl header and library files manually if brew link failed

  ```
  ln -s /usr/local/opt/libressl/include/openssl /usr/local/include/openssl
  ln -s /usr/local/opt/libressl/lib/libcrypto.a /usr/local/lib/libcrypto.a
  ln -s /usr/local/opt/libressl/lib/libcrypto.dylib /usr/local/lib/libcrypto.dylib
  ln -s /usr/local/opt/libressl/lib/libssl.a /usr/local/lib/libssl.a
  ln -s /usr/local/opt/libressl/lib/libssl.dylib /usr/local/lib/libssl.dylib
  ```
