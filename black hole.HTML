<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>黑洞乱码生成器</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: 'Courier New', monospace;
            background: #111;
            color: #0f0;
            line-height: 1.6;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: #222;
            padding: 2rem;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 255, 0, 0.1);
        }

        .input-group {
            margin-bottom: 1.5rem;
        }

        input[type="text"] {
            width: 100%;
            padding: 8px;
            margin: 8px 0;
            background: #333;
            color: #0f0;
            border: 1px solid #0f0;
            border-radius: 4px;
            font-family: inherit;
            font-size: 1rem;
        }

        input[type="range"] {
            width: 100%;
            margin: 10px 0;
            accent-color: #0f0;
        }

        .level-display {
            display: inline-block;
            margin-left: 10px;
            min-width: 40px;
            text-align: right;
        }

        button {
            background: #0a0;
            color: #000;
            border: none;
            padding: 10px 20px;
            margin: 10px 5px;
            border-radius: 4px;
            cursor: pointer;
            font-family: inherit;
            font-size: 1rem;
            transition: all 0.3s;
        }

        button:hover {
            background: #0f0;
            box-shadow: 0 0 10px rgba(0, 255, 0, 0.3);
        }

        textarea {
            width: 100%;
            height: 150px;
            padding: 10px;
            margin: 10px 0;
            background: #333;
            color: #0f0;
            border: 1px solid #0f0;
            border-radius: 4px;
            font-family: inherit;
            font-size: 1rem;
            resize: vertical;
        }

        .button-group {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            justify-content: center;
        }

        @media (max-width: 600px) {
            .container {
                padding: 1rem;
            }
            
            button {
                padding: 8px 16px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>黑洞乱码生成器</h1>
        
        <div class="input-group">
            <label for="in">输入底字（如 π、o、A）：</label>
            <input id="in" type="text" placeholder="输入底字（如 π、o、A）" value="o▬|🌌⃢">
        </div>

        <div class="input-group">
            <label>
                调整层数：
                <input id="level" type="range" min="10" max="800" value="200">
                <span class="level-display" id="lv">200</span> 层
            </label>
        </div>

        <div class="button-group">
            <button onclick="generateBlackHole()">生成黑洞</button>
            <button onclick="copyResult()">复制结果</button>
            <button onclick="randomGenerate()">随机生成</button>
        </div>

        <textarea id="out" readonly placeholder="生成的乱码将显示在这里..."></textarea>
    </div>

    <script>
        // 初始化时生成一次
        generateBlackHole();

        function generateBlackHole() {
            const base = document.getElementById('in').value || ' ';
            const n = parseInt(document.getElementById('level').value);
            const comb = ['\u0E31','\u0E34','\u0E35','\u0E36','\u0E37','\u0E38','\u0E39','\u0E47','\u0E48','\u0E49','\u0E4A','\u0E4B','\u0E4C','\u0E4D','\u0E4E'];
            
            let hat = '';
            for(let i = 0; i < n; i++) {
                hat += comb[i % comb.length];
            }
            
            const result = base + hat + '=========>';
            document.getElementById('out').value = result;
            document.getElementById('lv').textContent = n;
        }

        function copyResult() {
            const out = document.getElementById('out');
            if(out.value.trim() === '') {
                alert('请先生成乱码！');
                return;
            }
            out.select();
            document.execCommand('copy');
            alert('已复制到剪贴板！');
        }

        function randomGenerate() {
            // 随机生成底字（包含常见符号和字母）
            const randomChars = 'πoO0@#$%^&*AaBbCcDdEeFfGgHhIiJjKkLlMmNnSsZz🌌✨🌀▬|→↓↑';
            const randomBase = randomChars[Math.floor(Math.random() * randomChars.length)];
            document.getElementById('in').value = randomBase;
            
            // 随机生成层数（10-800之间）
            const randomLevel = Math.floor(Math.random() * 791) + 10;
            document.getElementById('level').value = randomLevel;
            
            // 实时更新层数显示并生成
            document.getElementById('lv').textContent = randomLevel;
            generateBlackHole();
        }

        // 滑块拖动时实时更新层数显示
        document.getElementById('level').addEventListener('input', function() {
            document.getElementById('lv').textContent = this.value;
        });
    </script>
</body>
</html>
