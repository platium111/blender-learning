1. User Interface
  Editor view (3D | image | Sculputure)
    Normally use 3D view
    Header | If not enough view for Header, using `Middle mouse`
  Display/hide | using N/T shortcut

2. Customizing layout
  Max wowrking area | `Ctril + space` or View -> Area -> Toggle ..
  Max more working area | `Ctril + cmd + space`
  Separate working area | In the right cornor, if display icon[][], can hold mouse and drag
    if has greater than 2, can swap view by `holding Ctril` and drag to another view
    Merge view | in the `right corner, hold and drag` to another view
    Isolate view | `Shift + hold right corner`
  Header top or bottom | right click in the Header and choose Top or Bottom
  Rearrage section panel inside area | Hold section and rearrange
  Text size change | `Ctril + middle mouse move`
  Save setting | Setting in top view -> File -> Default ...-> Save file

3. Workspace
  In the middle top, see Layout, Modelling, UV Setting... -> each one is setup for specicial use
  Add working space | In the right has + button then choose Duplicate Current View
    Can Save working space, if not we're not saving the view


4. Mode
  Image mode
    Can choose image => paint, it will affect to the 3D View
  UV Editor 
    can see Line as smart object
  Shade Editor
    Table connect (each one is node)
  Composite Editor
    Create animation, video, for example glow effect in the middle of 2 nodes
  Texture editor
    Create brick, cloud..,.
  Sequence Editor
    Working with Video Edit
  Video Editor
    Tracking point in something in the video. When video start, points will be tracking in the line -> can add mode 3D to make it as the move
  Animation editor (dope sheet)
    Frame 1, `press I` -> choose Location. Then frame 10, use G to move the 3D -> press I choose Location -> Finally use play it likes the video
    Can create faster animation by Select point in Dope Sheet -> drag to make it smaller
  Timeline editor
    as Area 3
  Graph Editor
    see graph 
    can change 3D move by changing graph with Action, exmaple YEuler Rotation Action
  Driver Editor
    2 Object 2D interact together, example Axis and gear
  Non-linear Editor
    Action as walking, raise hand...for people example.  
  Scripting editor
    Viết code, note -> có thể chạy Run Script
    Muốn hiển thị console vào Window -> Toggle System Console 
  Python console
    Có sẵn api cho python, ví dụ viết dir() sẽ hiển thị thư mục
  Info editor 
    Sẽ thấy các thứ ta làm trong blender
  Data Editor (Outliner)
    Là phần Area 2 có scene collection như camera, line, cube
    Có thể hidden một số obj hoặc organise nó thành các collection

Properties
    là phần Area 3
File browser
  Để import/export file là chủ yếu
Toolbar
  Vào mục Edit
    Interface dùng để thay đổi reesolutiob hay Navigation Control
    Theme | sẽ có thay đỏi vertex size
    Light | sẽ thay đổi Editor Studio Light
    Navigation
      dấu tick vào Orbit Around thì có thể chọn obj và quay xung quanh
      Zoom mouse | có thể ấn vào đâu đó xong zoom nó sẽ vào điểm đó
    Hotkey
      Chọn ở đây hoặc vào các menu item xong chuột phải để Assign hotkey
Save
  AAnns +/- nếu muốn thay đổi copy index
  Save copy 
    dung để save backup file
Backup
  File -> Recover -> last session (dùng khi dont save khi Quit)
Import/Export
  Nếu muốn import và export các định dạng # thì vào Setting -> Preference -> Addon -> Import/Export
Object Type of See
  Theo Numpaf thì 1 là nhìn chính diện, 3 là sideview, top 7
  2,8 là trái /phải 15 độ
  Tọa độ x,y,z cũng có thể nhìn object theo 3 chiều
Unit measurement
  Vào Area 3 có mục tam giác và dấu tròn sẽ thấy Units
  Có thể chia 1 ô to thành 12 ô nhỏ vào subdivition ở phần tròn/tam giác phía bên trên phải
Shading (trên phải top)
  Ấn Z để xem options gồm Wireframe mode, solid mode...
  Ấn Ctril + Z để chuyển nhanh sang wireframe mode
  Thông thưỡng sẽ thấy bên trong độ lõm thế nào, nếu chọn option (dấu mũi xuống ở top right sẽ thấy Backface culling) -> không nhìn thẫy lõm khi view bên trong
  Chỉnh color
    vào phần Clor -> SIngle -> sẽ change đc color
  X ray
    tạo transparent, rất quan trọng vì nhìn các điểm xuyên thấu được, kết hợp với G có thể edit model trực tiếp
    