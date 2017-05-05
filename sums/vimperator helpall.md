liberator://help/all
3.15.0 161005

[toc]
#1 introduction
#2 Starting Vimperator
##2-1 Initialization
###:source
```
echo 'echo 1' > ~/vimp
```
:source ~/vimp
#3 Browsing
##3-2 Opening web pages
###:tabopen
`:tabopen www.baidu.com`
#4 buffer
#5 command-line mode
#6 insert mode
#7 Options
google vimperator  about config
https://evanhahn.com/configure-firefox-with-vimperator/
```
:set! browser.startup.homepage=https://duckduckgo.com/
:set! browser.startup.homepage
```
##7-3 List of options
###'focuscontent' 'fc'
`set fc=true`
C-t，处于normal模式

`set fc=true`
C-t，处于insert模式，定位于地址栏
#8 text search commands
#9 tabs
#10 hints
#11 Key mappings, abbreviations, and user-defined commands
##11-1 Key mapping
###11-1-3 Key sequences
####CR
`:noremap <Leader>1 :tabopen www.baidu.com<CR>`
sum:leader cr小写也可以

####Leader
`:noremap <Leader>1 :tabopen www.baidu.com`
#12 expression evaluation
#13 marks
#14 bookmarks
#15 history
#16 quickmarks
#17 local marks
#18 repeating commands
#19 automatic commands
#20 printing
#21 vimperator's gui
#22 styling the gui and we pages
#23 error and informational messages
#24 developer information
#25 other help
#26 using plugins
