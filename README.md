
## Members:
Đinh Xuân Quyền
Phan Văn Tình
Tạ Văn Thanh
## Introduction
Ứng dụng nghe nhạc số cơ bản, người dùng sẽ có các chức năng nghe và phát nhạt, tạo danh sách các bài hát  
# Structural Diagram
## UML diagram 
![image](https://github.com/user-attachments/assets/e0fc8ef5-aadf-42d5-80b5-761dd3621475)
## Sequence diagram
Chức năng tạo danh sách bài hát
![image](https://github.com/user-attachments/assets/0c4677fa-786f-4ff5-a097-576af32c291b)
Chức năng xóa bài hát khỏi danh sách 
![image](https://github.com/user-attachments/assets/c2fff65b-c83a-4296-8155-0816f8612886)
Chức năng phát và dừng nhạc
![image](https://github.com/user-attachments/assets/4743ffc2-70cc-4391-b5e9-0d8e642d5535)
Chức năng tua bài hát
![image](https://github.com/user-attachments/assets/76ec0265-ceb4-49a1-b016-9dd28dff1cba)



## Activity Diagram
Chức năng xóa bài hát
![image](https://github.com/user-attachments/assets/8c95d73e-b64b-4a24-96b1-b9357b2ea162)
Chức năng chơi và phát nhạc 
![image](https://github.com/user-attachments/assets/b694f21f-3f4e-4fec-b9f5-fe6085938f46)
Chức năng thêm và xóa bài hát 
![image](https://github.com/user-attachments/assets/978f7385-49ed-49a2-9c4d-a3ab1b5686ea)
Chức năng tạo danh sách phát mới
![image](https://github.com/user-attachments/assets/366417d8-5419-4657-9e27-475eb8afbb62)




## Class Diagram

Class User {
  int UserId;
  
  String name;
  
  String email;
},


Class Playlist{
  List<Track> tracks = []; 
  
  int PlayId;
  
  String Namesong;
  
  String Author;
  
  String description;
  
  DateTime createdAt;
  
  DateTime updatedAt;      
  
  bool repeat = false;   
  
  bool isPlaying = false;         
}


class Song {
  String title;         
  
  String artist;   
  
  int duration;    
  
  String genre;    
  
  int releaseYear;   
  
  String album;        
  
  String audioFormat;  
  
  }
