<h1 align='center'><font color='#2780e3'>  Vocabulary-of-CET-4 </font></h1>

> 这是一个从网上爬取、整理的英语四级单词库
------------------------------

## 实现数据类型
- 文本文件 &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :white_check_mark:
- JSON &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :white_check_mark:
- XML &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :negative_squared_cross_mark:
- Oracle文件 &ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :negative_squared_cross_mark:
- Mysql文件 &thinsp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :negative_squared_cross_mark:
- PostgreSQL文件 &thinsp;&ensp; :negative_squared_cross_mark:
- SQLServer文件 &thinsp;&ensp;&ensp; :white_check_mark:
- Excel文件 &ensp;&ensp;&ensp;&ensp;&ensp;&ensp;&ensp; :negative_squared_cross_mark:

## 词库目录结构

├── TXT // TXT文本单词库  
│ ├── 总表 // 总的文本文件  
│ │ └── 四级词汇总表.txt // 总的文本文件  
│ └── 字母表 // 首字母单词表  
│   ├── A.txt   
│   ├── B.txt  
│   └── ...  
├── JSON  //JSON文件的单词库
└── SQLServer // SQL server单词库  
  ├── Words.mdf // 数据库文件  
  └── Words_log.ldf // 日志文件  

## SQL Server数据库设计

### cet_4  
name | type |  info  
-|-|-
wid | int | 单词ID;自增 |
word | nvarchar(30) | 单词 |
phonetic_symbol | nvarchar(30) | 音标 |
mean | nvarchar(50) | 释义 |
initial | nvarchar(50) | 首字母 |

## 最后

> 如果这个词库对您有所帮助，请帮忙点亮右上方的小星星，蟹蟹啦！:kissing_heart:  
