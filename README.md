######################
#### # Tsali
#### # 2019/05/28
#### # ncm -- For back-ups on same box
#### # ncm-scp -- For back-ups on a remote box
#### # See each file for more explicit details
######################

This is a simple script that e-mails a device config that exists in the NCM folder on a Back-up server.
2025/03/04 -- This was built specifically for use within the network at my emplyoer at that time, but the basic principals should still apply.

To install
1. Log into the linux server you're installing it in
2. git clone https://github.com/tsali/ncm.git
3. cd into the ncm directroy
4. chmod +x nc*
4. use from within the ncm directory (IE ./ncm ./ncm-scp or bash ncm) or copy to /bin or /usr/bin as necessary

For the copy/paste inclined:

```
git clone https://github.com/tsali/ncm.git && cd ncm && chmod +x nc*
```

