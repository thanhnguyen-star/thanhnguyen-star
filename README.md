<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio | System Engineer</title>

    <!-- FONT -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
        }

        body{
            background:#050b16;
            color:#fff;
            font-family:'Inter',sans-serif;
            padding:40px 20px;
        }

        .container{
            max-width:900px;
            margin:auto;
            border:1px solid #1f2937;
            padding:40px;
            background:#070d18;
            border-radius:10px;
        }

        h1{
            text-align:center;
            font-size:42px;
            margin-bottom:25px;
            font-weight:700;
        }

        hr{
            border:none;
            height:1px;
            background:#2b3648;
            margin:30px 0;
        }

        .tags{
            display:flex;
            justify-content:center;
            gap:10px;
            flex-wrap:wrap;
            margin-bottom:25px;
        }

        .tag{
            padding:8px 16px;
            font-size:13px;
            font-weight:700;
            border-radius:4px;
            text-transform:uppercase;
            letter-spacing:1px;
        }

        .gray{ background:#4b5563; }
        .blue{ background:#2563eb; }
        .purple{ background:#7c3aed; }
        .white{
            background:#f3f4f6;
            color:#000;
        }

        .social{
            text-align:center;
            margin-top:10px;
        }

        .social a{
            display:inline-block;
            text-decoration:none;
            color:#fff;
            padding:8px 14px;
            margin:5px;
            border-radius:4px;
            font-size:14px;
            font-weight:600;
        }

        .gmail{
            background:#ea4335;
        }

        .linkedin{
            background:#0a66c2;
        }

        .section-title{
            font-size:28px;
            margin-bottom:20px;
            font-weight:700;
        }

        .quote{
            color:#9ca3af;
            font-style:italic;
            border-left:3px solid #64748b;
            padding-left:15px;
            margin-bottom:25px;
        }

        p{
            line-height:1.8;
            font-size:17px;
            margin-bottom:20px;
        }

        ul{
            padding-left:25px;
        }

        li{
            margin-bottom:14px;
            line-height:1.7;
            font-size:17px;
        }

        .stack-table{
            width:100%;
            border-collapse:collapse;
            margin-top:20px;
        }

        .stack-table th,
        .stack-table td{
            border:1px solid #334155;
            padding:18px;
            vertical-align:top;
        }

        .stack-table th{
            background:#0f172a;
            font-size:18px;
        }

        .skill{
            display:inline-block;
            padding:6px 12px;
            border-radius:4px;
            margin:5px 5px 0 0;
            font-size:13px;
            font-weight:600;
        }

        .python{ background:#3776ab; }
        .cpp{ background:#2563eb; }
        .bash{ background:#22c55e; }

        .docker{ background:#0ea5e9; }
        .linux{ background:#eab308; color:#000; }
        .nginx{ background:#22c55e; }

        .wazuh{ background:#000; }
        .mitre{ background:#f97316; }
        .syslog{ background:#3b82f6; }

        .git{ background:#ef4444; }
        .profile{ background:#64748b; }
        .anki{ background:#f59e0b; }

        .update{
            text-align:right;
            margin-top:25px;
            color:#e5e7eb;
            font-style:italic;
        }

        @media(max-width:768px){

            h1{
                font-size:30px;
            }

            .container{
                padding:25px;
            }

            .stack-table th,
            .stack-table td{
                padding:12px;
            }
        }
    </style>
</head>
<body>

    <div class="container">

        <h1>Ngô Đức Vương | System Engineer</h1>

        <div class="tags">
            <div class="tag gray">OS</div>
            <div class="tag blue">ARCH LINUX</div>
            <div class="tag gray">WM</div>
            <div class="tag purple">NIRI / HYPRLAND</div>
            <div class="tag gray">SHELL</div>
            <div class="tag white">ZSH</div>
        </div>

        <div class="social">
            <a href="#" class="gmail">Email</a>
            <a href="#" class="linkedin">LinkedIn</a>
        </div>

        <hr>

        <div class="about">

            <div class="section-title">🖥 whoami</div>

            <div class="quote">
                "Fast and concise. Systems are meant to be built, broken, and optimized."
            </div>

            <p>
                Tôi là sinh viên <b>Saigon Technology University (STU)</b> và là một
                Software Engineer với đam mê sâu sắc về hạ tầng hệ thống và an ninh mạng.
                Hiện tại, tôi đang tập trung vào:
            </p>

            <ul>
                <li>
                    🛡 <b>LSMP (Lightweight Security Monitoring):</b>
                    Xây dựng giải pháp giám sát nhẹ cho SME
                    (Wazuh, Docker, Syslog).
                </li>

                <li>
                    🏗 <b>System Infrastructure:</b>
                    Tối ưu hóa môi trường làm việc trên Linux
                    (Arch, Wayland).
                </li>

                <li>
                    🧠 <b>Algorithms:</b>
                    Rèn luyện tư duy DSA bằng Python để giải quyết
                    các bài toán hệ thống.
                </li>
            </ul>

        </div>

        <hr>

        <div class="section-title">🛠 Technical Stack</div>

        <table class="stack-table">

            <tr>
                <th>Languages</th>
                <th>Infrastructure</th>
                <th>Security</th>
                <th>Tools</th>
            </tr>

            <tr>

                <td>
                    <span class="skill python">Python</span>
                    <span class="skill cpp">C++</span>
                    <span class="skill bash">Bash</span>
                </td>

                <td>
                    <span class="skill docker">Docker</span>
                    <span class="skill linux">Linux</span>
                    <span class="skill nginx">Nginx</span>
                </td>

                <td>
                    <span class="skill wazuh">Wazuh</span>
                    <span class="skill mitre">MITRE ATT&CK</span>
                    <span class="skill syslog">Syslog</span>
                </td>

                <td>
                    <span class="skill git">Git</span>
                    <span class="skill profile">Profile</span>
                    <span class="skill anki">Anki Learning</span>
                </td>

            </tr>

        </table>

        <div class="update">
            Last Update: 2026.05.16 🚀
        </div>

    </div>

</body>
</html>
