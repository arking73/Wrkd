<!DOCTYPE html>
<html>
<head>
    <title>Funny Prank</title>
    <style>
        #freeze-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: white;
            z-index: 9999;
            display: none;
        }
    </style>
</head>
<body>
    <h1>🎉 Congrats! You won a prize! 🎉</h1>
    <p>Click the button below to claim it!</p>
    <button onclick="triggerFreeze()">CLICK HERE</button>

    <div id="freeze-overlay"></div>

    <script>
        function triggerFreeze() {
            const overlay = document.getElementById('freeze-overlay');
            overlay.style.display = 'block'; // स्क्रीन को "फ्रीज़" करने का नाटक
            setTimeout(() => {
                overlay.style.display = 'none'; // 5 सेकंड बाद ठीक हो जाएगा
            }, 5000 Wrkd
No
