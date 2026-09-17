# [vim使用](https://github.com/cherishyuan/blog/issues/4)

常用的插件：
```
" 快速跳转
Plug 'easymotion/vim-easymotion'
" 模糊查找文件，buffer，tag等
Plug 'Yggdroot/LeaderF'
" 对齐代码的虚线，写Python尤其需要
Plug 'Yggdroot/indentLine'
" 用不同颜色高亮单词或选中块
Plug 'Yggdroot/vim-mark'
" grep 文本，用过ag.vim, ack.vim还有grepxxx等
Plug 'dyng/ctrlsf.vim'
"亮光标处单词在文件的所有位置,k激活                                             
 Plug 'lfv89/vim-interestingwords'
"彩虹括号                                                                      
 Plug 'luochen1990/rainbow' 
```
相关配置：
```
 "彩虹括号                                                                       
 let g:rainbow_active = 1                                                        
                                                                                
 "vim-interestingwords 插件配置                                                  
 let g:interestingWordsGUIColors = ['#8CCBEA', '#A4E57E', '#FFDB72', '#FF7272', '    #FFB3FF', '#9999FF']                                                            
 let g:interestingWordsTermColors = ['154', '121', '211', '137', '214', '222']   
 let g:interestingWordsRandomiseColors = 1                                       
                                                                              
 "indentline config                                                              
let g:indentLine_setColors = 0                                                  
let g:indentLine_char_list = ['|', '¦', '┆', '┊']  
```


