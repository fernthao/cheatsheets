- Copy ssh public key to remote server  
`ssh-copy-id username@hostname`

- List hardware info  
  - inxi -F = full output, x adds details, z masks out personally identifying information like MAC and IP addresses.  
```
inxi -Fxz 
hwinfo --short
lshw -short
lscpu
```
- Fuzzy find with side preview  
`fzf --preview 'cat --color=always {}'`
