<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>健康建议助手</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .fade-in { animation: fadeIn 0.5s; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
        .card-hover:hover { transform: translateY(-5px); box-shadow: 0 10px 25px rgba(0,0,0,0.1); }
    </style>
</head>
<body class="bg-gradient-to-br from-blue-50 to-green-50 min-h-screen">
    <header class="bg-white shadow-sm">
        <div class="container mx-auto px-6 py-4">
            <h1 class="text-3xl font-bold text-blue-600">
                <i class="fas fa-heartbeat mr-2"></i>健康建议助手
            </h1>
        </div>
    </header>

    <main class="container mx-auto px-6 py-8">
        <div id="form-section" class="max-w-2xl mx-auto bg-white rounded-xl shadow-md overflow-hidden p-8 fade-in">
            <h2 class="text-2xl font-semibold text-gray-800 mb-6">健康情况调查</h2>
            
            <form id="health-form" class="space-y-6">
                <div>
                    <label class="block text-gray-700 mb-2">年龄</label>
                    <input type="number" name="age" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500" min="1" max="120" required>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">性别</label>
                    <div class="flex space-x-4">
                        <label class="inline-flex items-center">
                            <input type="radio" name="gender" value="male" class="h-5 w-5 text-blue-600" required>
                            <span class="ml-2">男性</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="radio" name="gender" value="female" class="h-5 w-5 text-blue-600">
                            <span class="ml-2">女性</span>
                        </label>
                    </div>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">身高 (cm)</label>
                    <input type="number" name="height" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500" min="100" max="250" required>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">体重 (kg)</label>
                    <input type="number" name="weight" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500" min="20" max="200" step="0.1" required>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">每周运动频率</label>
                    <select name="exercise" class="w-full px-4 py-2 border rounded-lg focus:ring-2 focus:ring-blue-500" required>
                        <option value="">请选择</option>
                        <option value="0">几乎不运动</option>
                        <option value="1-2">1-2次</option>
                        <option value="3-4">3-4次</option>
                        <option value="5+">5次以上</option>
                    </select>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">睡眠质量</label>
                    <div class="flex items-center space-x-4">
                        <span class="text-sm text-gray-500">差</span>
                        <input type="range" name="sleep" min="1" max="10" value="5" class="w-full h-2 bg-gray-200 rounded-lg appearance-none cursor-pointer">
                        <span class="text-sm text-gray-500">优</span>
                    </div>
                </div>

                <div>
                    <label class="block text-gray-700 mb-2">主要健康关注点 (可多选)</label>
                    <div class="grid grid-cols-2 gap-2">
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="weight" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">体重管理</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="sleep" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">睡眠改善</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="stress" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">压力管理</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="diet" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">饮食营养</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="fitness" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">体能提升</span>
                        </label>
                        <label class="inline-flex items-center">
                            <input type="checkbox" name="concerns" value="other" class="h-4 w-4 text-blue-600">
                            <span class="ml-2">其他</span>
                        </label>
                    </div>
                </div>

                <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-medium py-3 px-4 rounded-lg transition duration-300">
                    获取健康建议
                </button>
            </form>
        </div>

        <div id="result-section" class="hidden max-w-4xl mx-auto mt-8 fade-in">
            <div class="bg-white rounded-xl shadow-md overflow-hidden p-8 mb-6">
                <h2 class="text-2xl font-semibold text-gray-800 mb-4">您的健康分析</h2>
                <div id="bmi-result" class="mb-6 p-4 bg-blue-50 rounded-lg">
                    <h3 class="text-lg font-medium text-blue-800 mb-2">BMI指数</h3>
                    <div class="flex items-center">
                        <div class="w-full bg-gray-200 rounded-full h-4">
                            <div id="bmi-bar" class="bg-gradient-to-r from-blue-400 to-green-400 h-4 rounded-full" style="width: 0%"></div>
                        </div>
                        <span id="bmi-value" class="ml-4 font-bold text-gray-700">0</span>
                    </div>
                    <p id="bmi-category" class="mt-2 text-gray-600"></p>
                </div>

                <div class="grid md:grid-cols-2 gap-6">
                    <div class="p-4 bg-green-50 rounded-lg">
                        <h3 class="text-lg font-medium text-green-800 mb-2"><i class="fas fa-utensils mr-2"></i>饮食建议</h3>
                        <ul id="diet-advice" class="list-disc pl-5 text-gray-700 space-y-1"></ul>
                    </div>
                    <div class="p-4 bg-purple-50 rounded-lg">
                        <h3 class="text-lg font-medium text-purple-800 mb-2"><i class="fas fa-running mr-2"></i>运动建议</h3>
                        <ul id="exercise-advice" class="list-disc pl-5 text-gray-700 space-y-1"></ul>
                    </div>
                    <div class="p-4 bg-yellow-50 rounded-lg">
                        <h3 class="text-lg font-medium text-yellow-800 mb-2"><i class="fas fa-bed mr-2"></i>睡眠建议</h3>
                        <ul id="sleep-advice" class="list-disc pl-5 text-gray-700 space-y-1"></ul>
                    </div>
                    <div class="p-4 bg-red-50 rounded-lg">
                        <h3 class="text-lg font-medium text-red-800 mb-2"><i class="fas fa-heartbeat mr-2"></i>健康提醒</h3>
                        <ul id="health-warnings" class="list-disc pl-5 text-gray-700 space-y-1"></ul>
                    </div>
                </div>
            </div>

            <div class="text-center">
                <button id="reset-btn" class="px-6 py-2 bg-gray-200 hover:bg-gray-300 text-gray-800 rounded-lg transition duration-300">
                    <i class="fas fa-redo mr-2"></i>重新填写问卷
                </button>
            </div>
        </div>
    </main>

    <footer class="bg-white border-t mt-12 py-6">
        <div class="container mx-auto px-6 text-center text-gray-500">
            <p>© 2025 健康建议助手 - 本建议仅供参考，具体健康问题请咨询专业医生</p>
        </div>
    </footer>

    <script>
        document.getElementById('health-form').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // 收集表单数据
            const formData = new FormData(this);
            const data = Object.fromEntries(formData.entries());
            data.concerns = formData.getAll('concerns');
            
            // 计算BMI
            const height = parseFloat(data.height) / 100;
            const weight = parseFloat(data.weight);
            const bmi = (weight / (height * height)).toFixed(1);
            
            // 显示结果区域
            document.getElementById('form-section').classList.add('hidden');
            document.getElementById('result-section').classList.remove('hidden');
            
            // 更新BMI显示
            document.getElementById('bmi-value').textContent = bmi;
            const bmiBar = document.getElementById('bmi-bar');
            
            // BMI分类和建议
            let bmiCategory = '';
            let bmiColor = 'from-blue-400 to-green-400';
            if (bmi < 18.5) {
                bmiCategory = '偏瘦 - 建议增加营养摄入';
                bmiBar.style.width = '20%';
                bmiColor = 'from-blue-400 to-blue-600';
            } else if (bmi < 24) {
                bmiCategory = '正常 - 保持健康生活习惯';
                bmiBar.style.width = '50%';
            } else if (bmi < 28) {
                bmiCategory = '超重 - 建议适当控制饮食并增加运动';
                bmiBar.style.width = '70%';
                bmiColor = 'from-yellow-400 to-orange-400';
            } else {
                bmiCategory = '肥胖 - 建议咨询医生制定减重计划';
                bmiBar.style.width = '90%';
                bmiColor = 'from-red-400 to-red-600';
            }
            
            bmiBar.className = `bg-gradient-to-r ${bmiColor} h-4 rounded-full`;
            document.getElementById('bmi-category').textContent = bmiCategory;
            
            // 生成个性化建议
            generateAdvice(data, bmi);
        });
        
        function generateAdvice(data, bmi) {
            const dietAdvice = document.getElementById('diet-advice');
            const exerciseAdvice = document.getElementById('exercise-advice');
            const sleepAdvice = document.getElementById('sleep-advice');
            const healthWarnings = document.getElementById('health-warnings');
            
            // 清空现有建议
            dietAdvice.innerHTML = '';
            exerciseAdvice.innerHTML = '';
            sleepAdvice.innerHTML = '';
            healthWarnings.innerHTML = '';
            
            // 基础饮食建议
            addAdviceItem(dietAdvice, '每天摄入5种不同颜色的蔬菜水果');
            addAdviceItem(dietAdvice, '控制精制糖和加工食品的摄入');
            
            // 根据BMI调整饮食建议
            if (bmi < 18.5) {
                addAdviceItem(dietAdvice, '增加优质蛋白质摄入，如鸡蛋、鱼类、豆类');
                addAdviceItem(dietAdvice, '适当增加健康脂肪，如坚果、鳄梨');
            } else if (bmi >= 24) {
                addAdviceItem(dietAdvice, '控制总热量摄入，减少高糖高脂食物');
                addAdviceItem(dietAdvice, '增加膳食纤维摄入，帮助控制食欲');
            }
            
            // 运动建议
            if (data.exercise === '0') {
                addAdviceItem(exerciseAdvice, '从每天15分钟步行开始，逐渐增加运动量');
                addAdviceItem(exerciseAdvice, '尝试每周增加2-3次中等强度运动');
            } else if (data.exercise === '1-2') {
                addAdviceItem(exerciseAdvice, '保持现有运动频率，尝试增加运动强度');
                addAdviceItem(exerciseAdvice, '加入力量训练，每周1-2次');
            } else {
                addAdviceItem(exerciseAdvice, '继续保持良好的运动习惯');
                addAdviceItem(exerciseAdvice, '注意运动多样化，避免过度训练');
            }
            
            // 睡眠建议
            if (parseInt(data.sleep) < 5) {
                addAdviceItem(sleepAdvice, '建立规律的睡眠时间表，每天同一时间上床');
                addAdviceItem(sleepAdvice, '睡前1小时避免使用电子设备');
                addAdviceItem(sleepAdvice, '尝试冥想或深呼吸练习帮助入睡');
            } else if (parseInt(data.sleep) < 7) {
                addAdviceItem(sleepAdvice, '改善睡眠环境，保持卧室黑暗、安静、凉爽');
                addAdviceItem(sleepAdvice, '限制午睡时间不超过30分钟');
            } else {
                addAdviceItem(sleepAdvice, '继续保持良好的睡眠习惯');
            }
            
            // 健康关注点建议
            if (data.concerns.includes('weight')) {
                addAdviceItem(healthWarnings, '定期监测体重变化，建议每周同一时间测量');
            }
            if (data.concerns.includes('stress')) {
                addAdviceItem(healthWarnings, '每天安排10-15分钟放松时间，练习正念减压');
            }
            if (data.concerns.includes('diet')) {
                addAdviceItem(dietAdvice, '记录饮食日记，帮助了解饮食习惯');
            }
            
            // 年龄相关建议
            if (parseInt(data.age) > 40) {
                addAdviceItem(healthWarnings, '建议每年进行一次全面体检');
                addAdviceItem(exerciseAdvice, '加入平衡训练，预防跌倒风险');
            }
        }
        
        function addAdviceItem(list, text) {
            const li = document.createElement('li');
            li.textContent = text;
            list.appendChild(li);
        }
        
        // 重置按钮功能
        document.getElementById('reset-btn').addEventListener('click', function() {
            document.getElementById('health-form').reset();
            document.getElementById('result-section').classList.add('hidden');
            document.getElementById('form-section').classList.remove('hidden');
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
    </script>
</body>
</html>
