<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GitHub Profile Card</title>
    
    <style>
        /* General Page Styling */
        body {
            background-color: #0d1117; /* GitHub Dark Mode Background */
            color: #c9d1d9;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        /* Card Container ID */
        #profile-card {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 24px;
            width: 300px;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
        }

        /* Avatar Image ID */
        #user-avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            border: 2px solid #30363d;
            object-fit: cover;
            margin-bottom: 12px;
        }

        /* Full Name ID */
        #user-name {
            font-size: 20px;
            font-weight: 600;
            color: #f0f6fc;
            margin: 0;
        }

        /* Username ID */
        #user-handle {
            font-size: 14px;
            color: #8b949e;
            margin: 4px 0 12px 0;
        }

        /* Bio ID */
        #user-bio {
            font-size: 14px;
            color: #c9d1d9;
            line-height: 1.4;
            margin-bottom: 16px;
        }

        /* Follow Button ID */
        #follow-btn {
            background-color: #21262d;
            color: #c9d1d9;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 6px 16px;
            font-size: 14px;
            font-weight: 500;
            cursor: pointer;
            width: 100%;
            margin-bottom: 20px;
            transition: background-color 0.2s;
        }

        #follow-btn:hover {
            background-color: #30363d;
            border-color: #8b949e;
        }

        /* Stats Layout ID */
        #stats-container {
            display: flex;
            justify-content: space-around;
            border-top: 1px solid #30363d;
            padding-top: 16px;
        }

        /* Stats Items Individual IDs */
        #stat-repos, #stat-followers, #stat-following {
            display: flex;
            flex-direction: column;
        }

        /* Classes for internal text inside stats (kept clean) */
        .count {
            font-size: 16px;
            font-weight: 600;
            color: #f0f6fc;
        }

        .label {
            font-size: 11px;
            color: #8b949e;
            margin-top: 2px;
        }
    </style>
</head>
<body>

    <div id="profile-card">
        <img id="user-avatar" src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?w=150" alt="Profile Picture">
        
        <h2 id="user-name">Mayank Dandare</h2>
        <p id="user-handle">@mahhi09</p>
        <p id="user-bio">Building cool things with code. Open source enthusiast and coffee lover. 🚀</p>
        
        <button id="follow-btn">Follow</button>
        
        <div id="stats-container">
            <div id="stat-repos">
                <span class="count">142</span>
                <span class="label">Repositories</span>
            </div>
            <div id="stat-followers">
                <span class="count">1.2k</span>
                <span class="label">Followers</span>
            </div>
            <div id="stat-following">
                <span class="count">430</span>
                <span class="label">Following</span>
            </div>
        </div>
    </div>

</body>
</html>
