<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        html,
        body {
            background-color: #0d1117;
            font-family: Arial, Helvetica, sans-serif;
        }
        h1 {
            font-size: 5vh;
        }
        .content {
            display: grid;
            grid-template-rows: repeat(5, 1fr);
            grid-template-columns: repeat(1, 1fr);
        }
        .aboutMe {
            font-size: 2vh;
        }
        .header {
            grid-row: 1/1;
        }
        .LeetCode {
            grid-row: 2/2;
        }
        .stats{
          grid-row:3/3;
        }
    </style>
</head>

<body>
    <div class="content">
        <div class="header">
            <h1>Hello there, I'm Kilian</h1>
            <div class="aboutMe">
                <p>Im a Computer Science Student at Bremerhaven University of Applied Sciences.</p>
                <p>In the last few months, I have developed a passion for creating dynamic, engaging, and responsive web
                    applications. My goal is to write code that is easy to understand, maintain, and build upon.</p>
            </div>
            <div class="goals">
                <p>🔭 I’m working on my <strong>Portfolio</strong> and <strong>Javascript</strong> skills.</p>
                <p>🌱 I’m developing my <strong>Javascript</strong> and <strong>CSS</strong> skills</p>
                <p>👀 I'm looking for an <strong>internship</strong> as <strong>Fullstack Developer</strong> in Germany
                    for my practical semester</p>
                <p>📫 How to reach me: <strong> Kilian_Voll@gmx.de </strong> </p>
            </div>
        </div>
        <div class="LeetCode">
            <h2>Improving my skills in problem solving</h2>
            <img width="100%" height="90%" scr="./metrics.plugin.leetcode.svg">
        </div>
        <div class="stats">
            <h2>My GitHub stats</h2>
        </div>
    </div>
</body>

</html>