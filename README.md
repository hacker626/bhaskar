# bhaskar
#Regarding internshala project
import sqlite3
book=sqlite3.connect(mylib.db)
cursbook=book.cursor()
cursbook.execute(CREATE TABLE book('''price, name, author, piece''');)
book.close()
