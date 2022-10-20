### 1.List转String数组

* 方法一:
```
//先准备一个List
List<String> testList=new ArrayList<>();
testList.add("a");
testList.add("b");
testList.add("c");
//List转String
String[] strs1=testList.toArray(new String[testList.size()]);
for(String s:strs1){
System.out.println(s);
}
```
* 方法二：
```
//先准备一个List
List<String> testList=new ArrayList<>();
testList.add("a");
testList.add("b");
testList.add("c");
//List转String
String[] strs2 = new String[testList.size()];
for(int i=0;i<testList.size();i++){
strs2[i]=testList.get(i);
}
for(String s:strs2){
System.out.println(s);
}
```

### 二：String数据转List

* 方法一：
```
//准备一个String数组
String[] strs = {"aa","bb","cc"};
//String数组转List
List<String> strsToList1= Arrays.asList(strs);
for(String s:strsToList1){
System.out.println(s);
}
```


* 方法二：
```
//准备一个String数组
String[] strs = {"aa","bb","cc"};
//String数组转List
List<String> strsToList2=new ArrayList<>();
Collections.addAll(strsToList2,strs);
for(String s:strsToList2){
System.out.println(s);
}
```

* 方法三：
```
//准备一个String数组
String[] strs = {"aa","bb","cc"};
//String数组转List
List<String> strsToList3=new ArrayList<>();
for(String s:strs){
strsToList3.add(s);
}
for(String s:strsToList3){
System.out.println(s);
}
```



 

 

 