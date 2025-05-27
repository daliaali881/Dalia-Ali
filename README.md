# Dalia-Ali
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dalia Ali - Digital Business Card</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        .card {
            max-width: 600px;
            margin: 20px auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            overflow: hidden;
        }
        .header {
            background-color: #4a69bd;
            color: white;
            padding: 30px 20px;
            text-align: center;
        }
        .header h1 {
            margin: 0;
            font-size: 28px;
        }
        .header h2 {
            margin: 10px 0 0;
            font-weight: normal;
            font-size: 18px;
        }
        .content {
            padding: 20px;
        }
        .contact-item {
            margin-bottom: 15px;
            padding-bottom: 15px;
            border-bottom: 1px solid #eee;
        }
        .contact-item:last-child {
            border-bottom: none;
        }
        .contact-item strong {
            display: inline-block;
            width: 100px;
        }
        .skills {
            margin-top: 20px;
        }
        .skills h3 {
            margin-bottom: 10px;
            color: #4a69bd;
        }
        .skill-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        .skill {
            background-color: #f0f0f0;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 14px;
        }
        .qr-section {
            margin-top: 20px;
            text-align: center;
        }
        .qr-section h3 {
            margin-bottom: 10px;
            color: #4a69bd;
        }
        .qr-code {
            width: 150px;
            height: 150px;
            margin: 0 auto;
            background-color: white;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .footer {
            background-color: #f9f9f9;
            padding: 15px;
            text-align: center;
            font-size: 14px;
            color: #777;
        }
        a {
            color: #4a69bd;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .two-columns {
            display: flex;
            flex-wrap: wrap;
        }
        .column {
            flex: 1;
            min-width: 250px;
            padding-right: 15px;
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="header">
            <h1>Dalia Ali</h1>
            <h2>Marketing & Relationship Manager | Business Development Consultant</h2>
        </div>
        
        <div class="content">
            <div class="two-columns">
                <div class="column">
                    <div class="contact-info">
                        <div class="contact-item">
                            <strong>Email:</strong> <span>Daliaali881@gmail.com</span>
                        </div>
                        <div class="contact-item">
                            <strong>Phone:</strong> <span>00971553688388</span>
                        </div>
                        <div class="contact-item">
                            <strong>LinkedIn:</strong> <a href="http://linkedin.com/in/dalia-ali-154995271" target="_blank">linkedin.com/in/dalia-ali-154995271</a>
                        </div>
                        <div class="contact-item">
                            <strong>Location:</strong> <span>Abu Dhabi, UAE</span>
                        </div>
                    </div>
                    
                    <div class="skills">
                        <h3>Expertise</h3>
                        <div class="skill-list">
                            <span class="skill">Marketing</span>
                            <span class="skill">Relationship Management</span>
                            <span class="skill">Business Development</span>
                            <span class="skill">Marketing Communications</span>
                            <span class="skill">Event Management</span>
                            <span class="skill">Communication Skills</span>
                            <span class="skill">Leadership</span>
                            <span class="skill">Problem Solving</span>
                        </div>
                    </div>
                </div>
                
                <div class="column">
                    <div class="qr-section">
                        <h3>Scan to view my digital card</h3>
                        <div class="qr-code">
                            <!-- This is a placeholder. You'll need to host this file online and then generate a QR code for that URL -->
                            <img src="https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://example.com/dalia_ali_card" alt="Business Card QR Code" width="150" height="150">
                        </div>
                        <p style="font-size: 12px; margin-top: 10px;">Note: Update QR code after hosting this card online</p>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="footer">
            <p>Created for IntraLogisteX MEA 2025</p>
        </div>
    </div>
</body>
</html>