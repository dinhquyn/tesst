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
Class Diagram

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
  DateTime createdAt;             // Ngày tạo Playlist
  DateTime updatedAt;             // Ngày cập nhật Playlist lần cuối
  bool repeat = false;            // Chế độ lặp lại (true/false)
  bool isPlaying = false;         // Trạng thái phát nhạc (đang chơi hay không)
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
