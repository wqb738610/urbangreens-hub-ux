# UrbanGreens Hub - Figma 制作步骤

目标：用 Figma 做 1 张 sitemap 和 3 张低保真 wireframes，然后导出 PNG 放回 A1.1 PDF，并把 Figma 分享链接粘到每张图的 caption 下面。

## 0. 新建 Figma 文件

1. 打开 Figma。
2. 新建 Design File，命名为 `FIT5032 A1.1 UrbanGreens Hub`.
3. 右上角点击 `Share`。
4. 权限设置为 `Anyone with the link can view`，之后复制链接备用。
5. 建议创建 4 个 Frame：
   - `Figure 1 - Sitemap`
   - `Figure 2 - Event Discovery and Registration`
   - `Figure 3 - Green Map and Site DiscoveryGreen Map and Site Discovery`
   - `Figure 4 - Admin Dashboard`

推荐每个 Frame 尺寸：`1440 x 960`。如果 Figma 里有 Desktop 预设，也可以选择 Desktop 宽屏尺寸。线框图是低保真，不需要做成精美高保真 UI。

## 1. 统一样式

为了报告看起来一致，四张图都用同一套样式：

- 背景：白色或浅灰色
- 主色：深绿色
- 边框：灰绿色
- 文字：黑色/深灰
- 图形：矩形、线条、简单图标即可
- 不需要真实图片
- 不需要复杂颜色和装饰

建议在每个 Frame 顶部写标题，例如：

`UrbanGreens Hub - Sitemap`

或者：

`Wireframe 1 - Event Discovery and Registration`

## 2. Figure 1 - Sitemap

### 必须包含的一级页面

在顶部中间放一个 `Home`，下面分出 6 个一级页面：

- Learn
- Events
- Green Map
- Community
- Account
- Admin

### 每个一级页面下面放这些子页面

Learn:

- Biodiversity guide
- Native plants
- Resource articles

Events:

- Event listing
- Event detail
- Registration
- My bookings

Green Map:

- Planting sites
- Filters
- Site detail
- Directions

Community:

- Volunteer stories
- Ratings & reviews
- Impact gallery

Account:

- Login
- Register
- Profile
- Accessibility settings

Admin:

- Dashboard
- Manage events
- Volunteer table
- Export report

### 画法

1. 用矩形画 `Home`。
2. 用线条从 Home 连接到 6 个一级页面。
3. 每个一级页面下面用小矩形列出子页面。
4. 在图下方加一句说明：

`This sitemap separates public learning, volunteering, map-based discovery, account features, and admin operations.`

## 3. Figure 2 - Event Discovery and Registration

这张图对应 `BR (B.1): Validations`。

### 页面结构

画一个浏览器窗口或桌面网页框架，里面包含：

- 顶部导航栏
- 左侧 Filters 面板
- 中间 Event Cards
- 右侧 Registration Form

### 顶部导航

放这些导航项：

- Home
- Learn
- Events
- Green Map
- Community
- Login

### 左侧 Filters

放 5 个筛选框：

- Suburb
- Date range
- Skill level
- Accessible site
- Has spots left

### 中间 Event Cards

画 3 张活动卡片：

1. `Royal Park Habitat Day`
   - `Sat 22 Aug, 9:30 AM`
   - `12 spots left`

2. `Yarra Riverbank Planting`
   - `Sun 30 Aug, 10:00 AM`
   - `Accessible`

3. `Brunswick Pollinator Patch`
   - `Sat 5 Sep, 1:00 PM`
   - `Beginner friendly`

### 右侧 Registration Form

表单字段：

- Full name *
- Email *
- Emergency contact *
- Accessibility needs
- I agree to safety guidelines

按钮：

- Submit

在按钮上方加一个红色错误提示：

`Inline validation: please complete required fields.`

### 图下说明

在 Frame 底部加：

`This wireframe focuses on validated event registration, event filtering, and confirmation before submission.`

## 4. Figure 3 - Green Map and Site Discovery

这张图对应 `BR (E.2): Geo Location`。

### 页面结构

画一个浏览器窗口或桌面网页框架，里面包含：

- 左侧 Search and filters 面板
- 右侧大地图区域
- 地图上的路线/河流线条
- 3-5 个 location pins
- 一个 selected site 信息卡

### 左侧 Search and Filters

字段：

- Search suburb or postcode
- Tree planting
- Pollinator garden
- Accessible paths
- Open this weekend

### Selected Site Card

卡片内容：

`Selected site: Merri Creek Habitat Link`

`Next event: 30 Aug`

`Distance: 2.4 km`

`CTA: View details`

### 地图区域

1. 用浅灰/浅绿矩形表示地图。
2. 用细线画几条道路或河流。
3. 用圆点/定位针表示地点。
4. 右上角加一个小提示卡：

`Map controls: zoom, keyboard tab order, high-contrast mode, list alternative.`

### 图下说明

`This wireframe focuses on searching nearby planting sites, viewing site details, and supporting accessible alternatives to a visual map.`

## 5. Figure 4 - Admin Dashboard

这张图对应 `BR (C.2): Role-based Authentication`。

### 页面结构

画一个后台仪表盘：

- 左侧深色 Sidebar
- 右侧 Dashboard 内容区
- 顶部 KPI cards
- Volunteer registrations table
- Impact chart
- Export / Bulk email / Create event 按钮

### Sidebar 菜单

- Dashboard
- Events
- Volunteers
- Reviews
- Exports
- Settings

### KPI Cards

画 4 个小卡片：

- Registered users: 428
- Upcoming events: 18
- Trees pledged: 2,640
- Avg rating: 4.6/5

### Volunteer Table

表格列：

- Name
- Event
- Role
- Status

示例行：

- Maya | Royal Park | Volunteer | Confirmed
- Helen | Yarra | Resident | Pending
- Omar | Admin | Staff | Approved
- Lin | Brunswick | Volunteer | Waitlist

### 右侧 Impact 区域

画一个简单柱状图，并加按钮：

- Bulk email
- Create event
- Export CSV

### 图下说明

`This wireframe focuses on admin-only access, searchable volunteer data, exports, and impact monitoring.`

## 6. 导出 PNG

对每个 Frame：

1. 选中 Frame。
2. 右侧找到 `Export`。
3. 选择 `PNG`。
4. 点击 `Export Figure...`。
5. 文件命名建议：
   - `figma_sitemap.png`
   - `figma_wireframe_event.png`
   - `figma_wireframe_map.png`
   - `figma_wireframe_admin.png`

## 7. 放回报告

你导出 PNG 后，把它们发给我或放到这个文件夹：

`C:\Users\WQB\Desktop\FIT 5032\A1_1_UrbanGreensHub\figma_exports`

我可以继续帮你把四张图替换进 PDF，并把 Figma share link 粘到每张图 caption 里。

