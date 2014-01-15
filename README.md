Vim-Commands
============

Let's keep some quick and dirty Vim commands at the ready.

# Find and Replace / Code Cleanup

Find `===` without spaces before and after and add some spaces  
`:%s/\(\S\)===\(\S\)/\1 === \2/gc`

Find `==` without spaces before and after and add some spaces  
`:%s/\(\S\)==\(\S\)/\1 == \2/gc`

Find `=` without spaces before and after and add some spaces  
`:%s/\(\S\)=\(\S\)/\1 = \2/gc`

Find `if(` without space before the parenthesis and add a space
`%s/if(/if (/gI`

Donezo.  
