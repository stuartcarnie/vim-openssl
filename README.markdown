# openssl.vim
Pathogen-compatible version of [openssl.vim][1]

openssl is created by Noah Spurrier

## description

Edit OpenSSL encrypted files and turn Vim into a Password Safe!

This plugin enables reading and writing of files encrypted using OpenSSL. 
The file must have the extension of one of the ciphers used by OpenSSL. For 
example: 

    .des3 .aes .bf .bfa .idea .cast .rc2 .rc4 .rc5 

This will turn off the swap file and .viminfo log. The `openssl` command 
line tool must be in the path.

## license
Extracted from [vim.org][1]

> I release all copyright claims. This code is in the public domain. 
> Permission is granted to use, copy modify, distribute, and sell this 
> software for any purpose. I make no guarantee about the suitability of this 
> software for any purpose and I am not liable for any damages resulting from 
> its use. Further, I am under no obligation to maintain or extend this 
> software. It is provided on an 'as is' basis without any expressed or 
> implied warranty. 

[1]: http://www.vim.org/scripts/script.php?script_id=2012 "openssl.vim"