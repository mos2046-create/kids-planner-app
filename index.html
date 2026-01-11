<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>더와이즈영어 강일미사 플래너</title>
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- React & ReactDOM -->
    <script crossorigin src="https://unpkg.com/react@18/umd/react.production.min.js"></script>
    <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.production.min.js"></script>
    <!-- Babel -->
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <!-- Confetti -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
    
    <style>
        @import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');
        body { font-family: 'Pretendard', sans-serif; }
        .scrollbar-hide::-webkit-scrollbar { display: none; }
        .scrollbar-hide { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-orange-50">
    <div id="root"></div>

    <script type="text/babel">
        const { useState, useEffect } = React;

        // --- 아이콘 컴포넌트들 (SVG) ---
        const IconBookOpen = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M2 3h6a4 4 0 0 1 4 4v14a3 3 0 0 0-3-3H2z"/><path d="M22 3h-6a4 4 0 0 0-4 4v14a3 3 0 0 1 3-3h7z"/></svg>;
        const IconPencil = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M17 3a2.85 2.83 0 1 1 4 4L7.5 20.5 2 22l1.5-5.5Z"/><path d="m15 5 4 4"/></svg>;
        const IconVolume2 = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"/><path d="M15.54 8.46a5 5 0 0 1 0 7.07"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14"/></svg>;
        const IconCheckCircle = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"/><polyline points="22 4 12 14.01 9 11.01"/></svg>;
        const IconStar = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="currentColor" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>;
        const IconLeft = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="m15 18-6-6 6-6"/></svg>;
        const IconRight = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="m9 18 6-6-6-6"/></svg>;
        const IconTrophy = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M6 9H4.5a2.5 2.5 0 0 1 0-5H6"/><path d="M18 9h1.5a2.5 2.5 0 0 0 0-5H18"/><path d="M4 22h16"/><path d="M10 14.66V17c0 .55-.47.98-.97 1.21C7.85 18.75 7 20.24 7 22"/><path d="M14 14.66V17c0 .55.47.98.97 1.21C16.15 18.75 17 20.24 17 22"/><path d="M18 2H6v7a6 6 0 0 0 12 0V2Z"/></svg>;
        const IconHeadphones = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M3 14v3a2 2 0 0 0 2 2h2v-5H3z"/><path d="M17 19h2a2 2 0 0 0 2-2v-3h-4v5z"/><path d="M3 14v-2a9 9 0 0 1 18 0v2"/></svg>;
        const IconUser = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M19 21v-2a4 4 0 0 0-4-4H9a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>;
        const IconCalendar = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><rect width="18" height="18" x="3" y="4" rx="2" ry="2"/><line x1="16" x2="16" y1="2" y2="6"/><line x1="8" x2="8" y1="2" y2="6"/><line x1="3" x2="21" y1="10" y2="10"/></svg>;
        const IconDownload = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M21 15v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-4"/><polyline points="7 10 12 15 17 10"/><line x1="12" x2="12" y1="15" y2="3"/></svg>;
        const IconRotate = ({size, className}) => <svg xmlns="http://www.w3.org/2000/svg" width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round" className={className}><path d="M3 12a9 9 0 1 0 9-9 9.75 9.75 0 0 0-6.74 2.74L3 8"/><path d="M3 3v5h5"/></svg>;

        const App = () => {
            const [currentDay, setCurrentDay] = useState(1);
            const [completedTasks, setCompletedTasks] = useState({});
            const [userName, setUserName] = useState('');
            const [dayDates, setDayDates] = useState({});
            const [showResetConfirm, setShowResetConfirm] = useState(false);
            const totalDays = 12;

            useEffect(() => {
                try {
                    const savedTasks = localStorage.getItem('wisePlannerData');
                    const savedName = localStorage.getItem('wisePlannerName');
                    const savedDates = localStorage.getItem('wisePlannerDates');
                    if (savedTasks) setCompletedTasks(JSON.parse(savedTasks));
                    if (savedName) setUserName(savedName);
                    if (savedDates) setDayDates(JSON.parse(savedDates));
                } catch (e) { console.error(e); }
            }, []);

            useEffect(() => { localStorage.setItem('wisePlannerData', JSON.stringify(completedTasks)); }, [completedTasks]);
            useEffect(() => { localStorage.setItem('wisePlannerName', userName); }, [userName]);
            useEffect(() => { localStorage.setItem('wisePlannerDates', JSON.stringify(dayDates)); }, [dayDates]);

            const handleDateChange = (e) => {
                setDayDates(prev => ({ ...prev, [`day-${currentDay}`]: e.target.value }));
            };

            const handleReset = () => {
                setCompletedTasks({}); setUserName(''); setDayDates({}); setCurrentDay(1);
                localStorage.removeItem('wisePlannerData'); localStorage.removeItem('wisePlannerName'); localStorage.removeItem('wisePlannerDates');
                setShowResetConfirm(false);
            };

            // 수정된 리스트: 더와이즈영어 강일미사 커리큘럼 반영
            const dailyTasks = [
                { id: 'word_read', category: '단어 (Word)', title: '큰 소리로 읽기', desc: '5번, 7번, 10번 읽기', icon: IconVolume2, color: 'bg-red-100 text-red-600' },
                { id: 'word_write', category: '단어 (Word)', title: '공책에 단어 쓰기', desc: '5번, 7번, 10번 쓰기', icon: IconPencil, color: 'bg-red-100 text-red-600' },
                { id: 'mb_read', category: 'M.B(미션북)', title: 'Sentence structure', desc: 'Sentence structure', icon: IconBookOpen, color: 'bg-yellow-100 text-yellow-600' },
                { id: 'mb_trans', category: 'M.B(미션북)', title: '문장 해석하기', desc: 'Sentence translation', icon: IconBookOpen, color: 'bg-yellow-100 text-yellow-600' },
                { id: 'writing_etc', category: '쓰기 (Writing)', title: '영쓰/한쓰topic/book report', desc: '주제에 맞춰 글쓰기', icon: IconPencil, color: 'bg-green-100 text-green-600' },
                { id: 'leddi_read', category: '다독정독 (Leddi)', title: '집중 읽기', desc: 'Comprehension Quiz', icon: IconBookOpen, color: 'bg-blue-100 text-blue-600' },
                { id: 'class_check', category: '마무리 학습', title: '클카 / C5 / G', desc: '학습 완료 후 체크하기', icon: IconStar, color: 'bg-purple-100 text-purple-600' },
            ];

            const toggleTask = (taskId) => {
                const key = `day-${currentDay}-${taskId}`;
                const isNowCompleted = !completedTasks[key];
                setCompletedTasks(prev => ({ ...prev, [key]: isNowCompleted }));
                if (isNowCompleted) {
                    const dayTasksKeys = dailyTasks.map(t => `day-${currentDay}-${t.id}`);
                    const allOthersCompleted = dayTasksKeys.every(k => k === key || completedTasks[k]);
                    if (allOthersCompleted) triggerConfetti();
                }
            };

            const triggerConfetti = () => {
                if (window.confetti) {
                    window.confetti({ particleCount: 100, spread: 70, origin: { y: 0.6 }, colors: ['#FFB6C1', '#87CEEB', '#FFFACD', '#E6E6FA'] });
                }
            };

            const calculateProgress = () => {
                const dayTasksKeys = dailyTasks.map(t => `day-${currentDay}-${t.id}`);
                const completedCount = dayTasksKeys.filter(k => completedTasks[k]).length;
                return Math.round((completedCount / dailyTasks.length) * 100);
            };

            const exportToExcel = () => {
                let csvContent = "\uFEFFDay,날짜,카테고리,미션,세부내용,완료여부\n";
                for (let day = 1; day <= totalDays; day++) {
                    const date = dayDates[`day-${day}`] || '-';
                    dailyTasks.forEach(task => {
                        const isCompleted = completedTasks[`day-${day}-${task.id}`];
                        const status = isCompleted ? "완료 (O)" : "미완료 (X)";
                        csvContent += `${day},${date},${task.category},${task.title},${task.desc},${status}\n`;
                    });
                }
                const blob = new Blob([csvContent], { type: 'text/csv;charset=utf-8;' });
                const link = document.createElement('a');
                link.href = URL.createObjectURL(blob);
                link.download = `${userName || 'KidsPlanner'}_Progress.csv`;
                document.body.appendChild(link);
                link.click();
                document.body.removeChild(link);
            };

            const isDayComplete = calculateProgress() === 100;

            return (
                <div className="min-h-screen bg-orange-50 font-sans selection:bg-orange-200">
                    <div className="max-w-md mx-auto min-h-screen bg-white shadow-xl flex flex-col relative overflow-hidden">
                        <div className="bg-gradient-to-r from-orange-300 to-pink-300 p-6 rounded-b-[2.5rem] shadow-md z-10 relative">
                            <div className="flex justify-between items-start text-white mb-4">
                                <div className="flex-1">
                                    <h1 className="text-2xl font-bold tracking-tight mb-1">더와이즈영어 강일미사</h1>
                                    <div className="flex items-center gap-2 bg-white/20 p-1.5 rounded-lg w-fit backdrop-blur-sm">
                                        <IconUser size={16} className="text-white ml-1" />
                                        <input type="text" placeholder="이름을 써주세요" value={userName} onChange={(e) => setUserName(e.target.value)} className="bg-transparent border-none text-white placeholder-white/70 text-sm font-medium focus:ring-0 p-0 w-24 outline-none" />
                                    </div>
                                </div>
                                <div className="flex gap-2">
                                    <button onClick={() => setShowResetConfirm(true)} className="bg-white/20 p-2 rounded-full backdrop-blur-sm hover:bg-white/30 transition-colors"><IconRotate size={24} className="text-white" /></button>
                                    <button onClick={exportToExcel} className="bg-white/20 p-2 rounded-full backdrop-blur-sm hover:bg-white/30 transition-colors"><IconDownload size={24} className="text-white" /></button>
                                </div>
                            </div>
                            <div className="bg-white/90 rounded-2xl p-2 shadow-sm space-y-2">
                                <div className="flex items-center justify-between">
                                    <button onClick={() => setCurrentDay(d => Math.max(1, d - 1))} disabled={currentDay === 1} className="p-2 hover:bg-orange-100 rounded-full transition disabled:opacity-30 text-orange-600"><IconLeft size={24} /></button>
                                    <span className="font-bold text-lg text-orange-600">Day {currentDay}</span>
                                    <button onClick={() => setCurrentDay(d => Math.min(totalDays, d + 1))} disabled={currentDay === totalDays} className="p-2 hover:bg-orange-100 rounded-full transition disabled:opacity-30 text-orange-600"><IconRight size={24} /></button>
                                </div>
                                <div className="flex items-center justify-center gap-2 border-t border-gray-100 pt-2">
                                    <IconCalendar size={14} className="text-gray-400" />
                                    <input type="date" value={dayDates[`day-${currentDay}`] || ''} onChange={handleDateChange} className="bg-transparent border-none text-gray-600 text-sm p-0 focus:ring-0 font-medium outline-none" />
                                </div>
                            </div>
                        </div>
                        <div className="px-6 mt-6 mb-2">
                            <div className="flex justify-between text-sm font-bold text-gray-500 mb-1"><span>오늘의 진도</span><span className="text-orange-500">{calculateProgress()}%</span></div>
                            <div className="w-full bg-gray-100 h-4 rounded-full overflow-hidden"><div className="h-full bg-gradient-to-r from-orange-400 to-pink-400 transition-all duration-500 ease-out rounded-full" style={{ width: `${calculateProgress()}%` }} /></div>
                        </div>
                        <div className="flex-1 overflow-y-auto px-4 py-4 space-y-3 pb-24 scrollbar-hide">
                            {isDayComplete && (
                                <div className="mb-4 p-4 bg-green-100 rounded-2xl border-2 border-green-200 text-center animate-bounce">
                                    <p className="text-green-700 font-bold text-lg flex items-center justify-center gap-2"><IconTrophy size={24} />미션 성공! 참 잘했어요!</p>
                                </div>
                            )}
                            {dailyTasks.map((task) => {
                                const isCompleted = completedTasks[`day-${currentDay}-${task.id}`];
                                return (
                                    <div key={task.id} onClick={() => toggleTask(task.id)} className={`relative group flex items-center p-4 rounded-2xl border-2 transition-all duration-200 cursor-pointer select-none ${isCompleted ? 'bg-gray-50 border-gray-100 opacity-60 scale-[0.98]' : 'bg-white border-orange-100 hover:border-orange-300 shadow-sm hover:shadow-md'}`}>
                                        <div className={`p-3 rounded-xl mr-4 ${isCompleted ? 'bg-gray-200 text-gray-400' : task.color}`}><task.icon size={24} /></div>
                                        <div className="flex-1"><div className="text-xs font-bold text-gray-400 mb-0.5 uppercase tracking-wider">{task.category}</div><h3 className={`font-bold text-gray-800 ${isCompleted ? 'line-through text-gray-400' : ''}`}>{task.title}</h3><p className={`text-sm text-gray-500 ${isCompleted ? 'text-gray-300' : ''}`}>{task.desc}</p></div>
                                        <div className={`w-8 h-8 rounded-full border-2 flex items-center justify-center transition-colors ${isCompleted ? 'bg-green-500 border-green-500' : 'border-gray-200 group-hover:border-orange-300'}`}>{isCompleted && <IconCheckCircle className="text-white w-5 h-5" />}</div>
                                    </div>
                                );
                            })}
                        </div>
                        {showResetConfirm && (
                            <div className="absolute inset-0 bg-black/50 z-50 flex items-center justify-center px-4 backdrop-blur-sm">
                                <div className="bg-white rounded-3xl p-6 shadow-2xl max-w-sm w-full">
                                    <div className="text-center">
                                        <div className="bg-red-100 p-4 rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4"><IconRotate size={32} className="text-red-500" /></div>
                                        <h3 className="text-xl font-bold text-gray-800 mb-2">모든 기록을 지울까요?</h3>
                                        <div className="flex gap-3 mt-6"><button onClick={() => setShowResetConfirm(false)} className="flex-1 py-3 px-4 rounded-xl bg-gray-100 text-gray-700 font-bold">취소</button><button onClick={handleReset} className="flex-1 py-3 px-4 rounded-xl bg-red-500 text-white font-bold">네, 지워주세요</button></div>
                                    </div>
                                </div>
                            </div>
                        )}
                        <div className="absolute bottom-0 w-full h-12 bg-gradient-to-t from-white to-transparent pointer-events-none" />
                    </div>
                </div>
            );
        };

        const root = ReactDOM.createRoot(document.getElementById('root'));
        root.render(<App />);
    </script>
</body>
</html>
