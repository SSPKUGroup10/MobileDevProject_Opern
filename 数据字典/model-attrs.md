

## UserCreate
//  登录注册的时候使用这个类
int userId;
String userName;
String password;

## User
int userId;
String userName;
String password;
String token;

List< Group> joinedList;

//  一些华而不实的功能
enum sex;
List< User> friendList;
String signature;



## Group
int groupId;
String groupName;
int masterId;
String description;

String type;
String rule;
List< User> memberList;

//  未确定数据类型
? startAt;
? endAt;

## 