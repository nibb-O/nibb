<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    
    <!-- 这里是新增的 Tab Icon (Favicon) 代码 -->
    <!-- 替换 href 后面的网址为你自己的图标链接，或者本地图片路径（如 icon.png） -->
    <link rel="icon" type="image/x-icon" href="download.jpg">

    <!-- 引入 Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<!-- 背景色：从左上到右下的粉色系渐变 -->
<body class="bg-gradient-to-br from-pink-100 via-rose-200 to-pink-300 min-h-screen flex items-center justify-center p-4">

    <!-- 主卡片容器：半透明磨砂玻璃效果 -->
    <div class="bg-white/40 backdrop-blur-md rounded-3xl p-8 max-w-sm w-full text-center shadow-xl border border-white/50">
        
        <!-- 头像区域 -->
        <div class="flex justify-center mb-4">
            <img 
                src="download.jpg" 
                alt="Avatar" 
                class="w-32 h-32 rounded-full object-cover shadow-lg ring-4 ring-white"
            >
        </div>

        <!-- 名字 -->
        <h1 class="text-2xl font-bold text-gray-800 tracking-wide mb-1">Nib</h1>
        
        <!-- 简介 -->
        <p class="text-sm text-gray-600 mb-6">✨ 一句话介绍你自己 ✨</p>

        <p class="text-xs text-pink-700/60 mt-4 italic">Tab 图标已经配置好啦！</p>

    </div>

</body>
</html>
