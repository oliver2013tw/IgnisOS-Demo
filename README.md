🔥 IgnisOS v1.0 Inferno 官方使用手冊
這是一款基於 Arch Linux 核心構建，專為高效能與極致視覺體驗打造的現代化作業系統。
🛠️ 系統最低硬體需求 (Minimum Requirements)
為了確保 Hyprland 動態特效與加密模組能順暢運行，請確保您的裝置符合以下規格：
處理器 (CPU): 64 位元雙核心處理器 (支援 x86_64 指令集)。
記憶體 (RAM):
最低：2.0 GB (僅能運行基礎終端)。
建議：4.0 GB 以上 (流暢運行圖形介面與多工)。
顯示卡 (GPU): 支援 OpenGL 3.0 或以上之顯示晶片 (虛擬機請務必開啟 3D 加速)。
儲存空間: 至少 8 GB 之可用空間。
韌體模式: 建議使用 UEFI 引導。
🚀 流程與使用配置
1. 啟動與引導
將下載的 IgnisOS-v1-ISO.zip 解壓縮，獲取 .iso 映像檔。將其掛載至虛擬機 (如 VMware, VirtualBox, UTM) 或使用 Ventoy 製作啟動隨身碟。
2. 身份驗證程序
開機進入系統後，會自動觸發 Ignis-Auth 加密防護層：
畫面提示：[IgnisOS] 請輸入啟動金鑰以解鎖系統。
輸入金鑰：請輸入您專屬的授權代碼 (輸入時字元可能不會顯示，請直接輸入後按 Enter)。
成功驗證：系統將自動啟動 Hyprland 桌面環境。
3. 基本環境配置
預設 Shell: Zsh (配置 Zsh-Autosuggestions)。
視窗合成器: Wayland / Hyprland。
網路設定: 若無連網，請在終端機輸入 nmtui 進行圖形化連線。
✨ 核心功能說明
🔒 煉金安全層 (Alchemy Security)
系統核心級別的存取控制。在未通過金鑰驗證前，系統將維持在受限的終端模式，確保您的私有開發環境不被未經授權的人員進入。
🎨 獄火視覺引擎 (Inferno Visuals)
預裝高度自定義的 Hyprland。支援毛玻璃特效、動態視窗平鋪與平滑的動畫過渡，提供目前 Linux 領域最頂級的視覺互動體驗。
🛠️ 開發者工具鏈 (Dev-Stack)
GPU 加速終端: 內建 Kitty 終端機，降低渲染延遲。
程式語言環境: 預載 Python、NodeJS (pnpm)、Rust (rustup) 與 Docker。
現代化命令: 包含 eza (取代 ls)、bat (取代 cat)、btop (系統監控)。
🎹 常用快捷鍵 (Default Keybinds)
組合鍵
功能說明

Super + Q

開啟 Kitty 終端機

Super + D

開啟應用程式搜尋選單 (Rofi)

Super + E

開啟檔案管理員

Super + V

切換視窗浮動 / 平鋪模式

Super + C

關閉當前視窗

Super + M

退出 IgnisOS (回到登入界面)

IgnisOS - Forge your digital destiny.

本系統皆由AI開發
