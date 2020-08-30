# python_craweler 
## requests
1.1 get(html,params=dict,stream,cookies=dict,headers=dict,auth=tuple,timeout)
1.1.1 text(屬性)
1.1.1.1 encoding
1.1.2 url(屬性)
1.1.3 content(屬性)
1.1.4 raw(屬性)
1.1.4.1 read
1.1.5 json
1.1.6 status_code(屬性)=list,recursive
1.1.7 headers.get
1.2 post(html,data=dict)
1.2.1 text(屬性)
1.3 codes.ok,codes.all_good(屬性)
1.4 exceptions.Timeout,exceptions.RequestException,exceptions.HTTPError,exceptions.ConnectionError,exceptions.Time(屬性)
1.5 raise_for_status

## urllib.request
2.1 urlopen
2.1.1 read
## from bs4 import BeautifulSoup
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
3.2.4 find_all(text,class_,limit,href)
3.2.4.1 string(屬性)
3.2.5 select(text)
3.2.5.1 string(屬性)
3.2.5.2 children(屬性)
3.2.5.3 find_previous_sibling
3.2.6 select_one(text)
3.2.7 html(屬性)
3.2.7.1 name(屬性)
3.2.7.2 next_element.next_element(屬性)
3.2.7.2.1 name(屬性)
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



