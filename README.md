![image](https://github.com/user-attachments/assets/dfcae67a-839d-4f79-bde4-29ca65576e98)# Nhóm 12 - Music-app-
## Members:
Đinh Xuân Quyền
Phan Văn Tình
Tạ Văn Thanh
## Introduction
Play Music  
# Structural Diagram
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
