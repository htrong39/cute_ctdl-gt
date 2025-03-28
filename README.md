[Form1]
    ├─── [Danh sách dữ liệu]
    │     ├── songList (DoublyLinkedList)         // Danh sách bài hát chính
    │     ├── songHistory (DoublyLinkedList)      // Lịch sử phát
    │     ├── songQueue (DoublyLinkedList)        // Hàng đợi phát
    │     └── favoriteSongs (DoublyLinkedList)    // Danh sách yêu thích
    │
    ├─── [Cấu trúc dữ liệu]
    │     ├── Node
    │     │   ├── Data (string)
    │     │   ├── Previous (Node)
    │     │   └── Next (Node)
    │     └── DoublyLinkedList
    │         ├── Head (Node)
    │         ├── Tail (Node)
    │         ├── Count (int)
    │         └── Methods
    │             ├── AddFirst()
    │             ├── AddLast()
    │             ├── RemoveFirst()
    │             ├── Clear()
    │             ├── Find()
    │             ├── GetNodeAt()
    │             ├── Shuffle()
    │             └── MergeSort()
    │
    ├─── [Chức năng phát nhạc]
    │     ├── PlayCurrentSong()
    │     ├── PlayNextSong()
    │     ├── btnNext_Click()
    │     ├── btnPrevious_Click()
    │     ├── btnBack_Click()
    │     └── axWindowsMediaPlayer1_PlayStateChange()
    │
    ├─── [Quản lý danh sách]
    │     ├── btnOpenFile_Click()     // Mở file nhạc
    │     ├── btnShuffle_Click()      // Xáo trộn
    │     ├── btnMergeSort_Click()    // Sắp xếp
    │     ├── UpdateListBox()         // Cập nhật giao diện
    │     └── listBox1_SelectedIndexChanged()
    │
    ├─── [Chế độ phát]
    │     └── btnLoop_Click()         // Bật/tắt lặp
    │
    ├─── [Hàng đợi]
    │     ├── btnAddToQueue_Click()   // Thêm vào hàng đợi
    │     ├── btnClearQueue_Click()   // Xóa hàng đợi
    │     ├── btnPlayQueue_Click()    // Phát từ hàng đợi
    │     └── button1_Click()         // Hiển thị danh sách chờ
    │
    ├─── [Tìm kiếm & Gợi ý]
    │     ├── btnSearch_Click_1()     // Tìm kiếm theo chữ cái
    │     ├── ShowSuggestedSongs()    // Hiển thị gợi ý
    │     └── listBoxSuggestions_MouseDoubleClick() // Chọn bài từ gợi ý
    │
    ├─── [Yêu thích]
    │     ├── btnAddToFavorites_Click()  // Thêm vào yêu thích
    │     └── btnShowFavorites_Click()   // Hiển thị danh sách yêu thích
    │
    └─── [Thoát]
          └── btnExit_Click()         // Thoát ứng dụng
