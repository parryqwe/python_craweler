# python_craweler 
https://www.itread01.com/content/1546835412.html  
## requests
1.1 get(html,params=dict,stream,cookies=dict,headers=dict,auth=tuple,timeout)  
1.1.1 text(屬性)  
1.1.1.1 encoding  
1.1.1.2 splitlines  
1.1.2 url(屬性)  
1.1.3 content(屬性)  
1.1.4 raw(屬性)  
1.1.4.1 read  
1.1.5 json  
1.1.5.1 keys  
1.1.6 status_code(屬性)=list,recursive  
1.1.7 headers.get  
1.2 post(html,data=dict)  
1.2.1 text(屬性)  
1.3 codes.ok,codes.all_good(屬性)  
1.4 exceptions.Timeout,exceptions.RequestException,exceptions.HTTPError,exceptions.ConnectionError,exceptions.Time(屬性)  
1.5 raise_for_status  
1.6 post(html,data=dict)  
1.6.1 text(屬性)  
1.7 Session  
## urllib.request
2.1 urlopen  
2.1.1 read  
## from bs4 import BeautifulSoup
*find,find_all  
*select,select_one  
*find_parent,find_parents  
*find_previous_siblings,find_next_siblings  
*_class,.  
*limit  
*get
*getText
3.1 BeautifulSoup(html,'html.parser')  
3.2 BeautifulSoup(text,'lxml')  
3.2.1 prettify  
3.2.2 div(屬性)  
3.2.2.1 name,attrs,string,text(屬性)  
3.2.2.2 get_text  
3.2.3 find(name,id,text,class_,attrs=dict,href)  
3.2.3.1 string(屬性),parent.name(屬性)  
3.2.3.2 find_all(True,text=list,class_=list,recursive)  
3.2.3.3 next_elements(屬性)  
3.2.3.3.1 NavigableString,name(屬性)  
3.2.3.4 get  
3.2.4 find_all(text or list,class_ or 其他條件,limit)      
3.2.4.1 string(屬性)  
3.2.4.2 get  
3.2.5 select(text,limit)   
3.2.5.1 string(屬性)  
3.2.5.2 children(屬性)  
3.2.5.2.1 name,string(屬性)  
3.2.5.2.2 replace  
3.2.5.3 find_previous_sibling  
3.2.5.4 contents(屬性)  
3.2.5.4.1 span.string(屬性)  
3.2.5.5 descendants(屬性)   
3.2.5.5.1 name(屬性)  
3.2.5.6 strings(屬性)  
3.2.5.7 parent.name(屬性)  
3.2.5.8 find_parent  
3.2.5.8.1 name(屬性)   
3.2.5.9 parents(屬性)  
3.2.5.9.1 name(屬性)  
3.2.5.10 find_parents  
3.2.5.10.1 name(屬性)  
3.2.5.11 next_sibling.next_sibling,previous_sibling.previous_sibling(屬性)  
3.2.5.12 find_next_sibling  
3.2.5.12.1 name,span.string(屬性)  
3.2.6 select_one(text)   
3.2.7 html(屬性)  
3.2.7.1 name(屬性)  
3.2.7.2 next_element.next_element(屬性)  
3.2.7.2.1 name(屬性)  
3.2.7.3 head.title.string, head.meta\["charset"\],body.div.div.p.a.string  
3.2.8 title(屬性)  
3.2.8.1 name(屬性)  
3.2.8.2 previous_element.previous_element(屬性)  
3.2.8.2.1 name(屬性)  
3.2.9 new_tag(text,href)  
3.2.9.1 string(屬性)  
3.2.10 b(屬性)(針對資料tag有所不同,不一定為b)  
3.2.10.1 replace_with(new_tag)   
3.2.10.2 insert_before  
3.2.10.3 insert_after  
3.2.10.4 clear  
3.2.10.5 append(text or new_tag or new_string)  
3.2.10.6 name,string(屬性)  
3.2.11 new_string(text)  
3.2.12 text(屬性)  
## from urllib.parse import urlparse
4.1 urlparse(html)  
4.1.1 scheme,netloc,port,path,query  
## re  
5.1 compile(規則)  
5.1.1 match  
5.1.1.1 group,start,end,span  
5.1.2 search  
5.1.2.1 group,start,end,span  
5.1.3 findall  
## from urllib.request import urlopen
6.1 urlopen  
6.1.1 read  
## from selenium import webdriver
7.1 Chrome  
7.1.1 get  
7.1.2 quit  
7.1.3 maximize_window  
7.1.4 find_element_by_id,find_element_by_name,find_element_by_class_name,find_element_by_tag_name,find_element_by_css_selector,find_element_by_link_text,find_element_by_partial_link_text,find_element_by_xpath  
7.1.4.1 click  
7.1.4.2 send_keys  
7.2 ChromeOptions  
7.2.1 add_experimeental_option  
## hashlib
8.1 md5  
8.1.1 update  
8.1.1.1 hexdigest  
8.1.2 hexdigest  
## from firebase import firebase
9.1 FirebaseApplication(url,None)  
9.1.1 post  
9.1.2 get  
9.1.3 delete  
9.1.4 put  
## facebook
10.1 GraphAPI(access_token,version)  
10.1.1 get_object(id)  
10.1.2 get_object(list)   
10.1.3 get_connections(id,connection_name)  
10.1.4 delete_object(id)  
10.1.5 put_wall_post(message,attachment)  
