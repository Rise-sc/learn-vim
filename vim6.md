"The only limit to our realization of tomorrow is our doubts of today."
  — Franklin D. Roosevelt

"In the middle of difficulty lies opportunity."
  — Albert Einstein

"Do not go where the path may lead, go instead where there is no path and leave a trail."
  — Ralph Waldo Emerson

"Success is not final, failure is not fatal: It is the courage to continue that counts."
  — Winston Churchill

"What you do today can improve all your tomorrows."
  — Ralph Marston

"Your time is limited, so don’t waste it living someone else’s life."
  — Steve Jobs

"The best way to predict the future is to invent it."
  — Alan Kay
# vim搜索替换
substitute命令 
:[range]s[ubstitute]/{pattern}/{string}/[flags] [count]  
range: 作用的范围 
s[ubstitute]: 替换命令 
pattern: 要匹配的模式(可以用正则) 
string: 要替换的内容  
flags: 标识符(g:全部 ,c:逐个, i:忽略大小写, n:不执行替统计数量)  
count: 替换行的数量(一般省略) 

例如: 
what are you?  
:% s/what/how/g 将what替换为how
:% s/what//gin
