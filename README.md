<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mahmoud Hossam Gharib - Resume</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, Helvetica, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #3f5493;
        }

        h1, h2, h3, h4, h5, h6 {
            margin: 0;
            color: #2c3e50;
        }

        a {
            color: #236592;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        /* Container */
        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        /* Header */
        .header {
            text-align: center; /* Center the header content */
            margin-bottom: 30px;
            padding-top: 150px; /* Add padding to avoid overlap with the photo */
        }

        .header h1 {
            font-size: 2.5em;
            margin-bottom: 5px;
        }

        .header h2 {
            font-size: 1.5em;
            margin-bottom: 10px;
            color: #666;
        }

        .contact-info {
            margin-bottom: 20px;
        }

        .contact-info p {
            margin: 5px 0;
            color: #555;
        }

        .contact-info a {
            color: #3498db;
        }

        /* Photo */
        .photo {
            position: absolute;
            top: 20px;
            left: 50%; /* Center the photo horizontally */
            transform: translateX(-50%); /* Adjust for exact centering */
            width: 150px; /* Larger photo */
            height: 150px; /* Larger photo */
            border-radius: 50%;
            overflow: hidden;
            border: 3px solid #f4f5f6;
        }

        .photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Sections */
        .section {
            margin-bottom: 30px;
        }

        .section h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
            padding: 3px;
            text-align: center; /* Center the topic */
            background-color: #2a91db; /* Blue background */
            color: #fff; /* White text */
            border-radius: 5px; /* Rounded corners */
            transition: background-color 0.3s ease, color 0.3s ease; /* Smooth transition */
        }

        /* Hover effect for section headings */
        .section h3:hover {
            background-color: #2a91db9b; /* Change background color on hover */
            color: #fff; /* Change text color on hover */
        }

        .section h4 {
            font-size: 1.5em;
            margin-bottom: 5px;
            color: #2a91db;
        }

        .section p {
            margin: 5px 0;
            color: #424141;
        }

        .section ul {
            list-style-type: disc;
            margin-left: 20px;
        }

        .section ul li {
            margin-bottom: 10px;
            color: #555;
        }

        /* Skills Section */
        .skills ul {
            display: flex;
            flex-wrap: wrap;
            list-style-type: none;
            padding: 0;
        }

        .skills ul li {
            background-color: #3498db;
            color: #fff;
            padding: 8px 15px;
            margin: 5px;
            border-radius: 5px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Photo -->
        <div class="photo">
            <img src="c:\Users\moh75\Desktop\profile-pic (4).png" alt="Profile Photo">
        </div>

        <!-- Header -->
        <div class="header">
            <h1>Mahmoud Hossam Gharib</h1>
            <h2>Network Engineer</h2>
            <div class="contact-info">
                <p>Phone: 01100345226</p>
                <p>Mail: <a href="mailto:mahmoud.hosamm2003@gmail.com">mahmoud.hosamm2003@gmail.com</a></p>
                <p>Address: Cairo, Egypt</p>
                <p>LinkedIn: <a href="https://www.linkedin.com/in/mahmoud-hossam-a160392a0">LinkedIn Profile</a></p>
                <p>Military Status: Completed</p>
            </div>
        </div>

        <!-- Objectives Section -->
        <div class="section objectives">
            <h3>Objectives</h3>
            <p>
                I am still learning, and I have a year left until graduation. I am looking for a challenge in a prestigious company to use my experience in this field and learn more from the company’s experts and develop my skills in the field of network engineering and system administration while contributing to the company’s growth.
            </p>
        </div>

        <!-- Education Section -->
        <div class="section education">
            <h3>Education</h3>
            <p>
                Faculty of Education - Higher Technological Institute, 10th of Ramadan City<br>
                Computer Science Branch, 2021-2025
            </p>
        </div>

        <!-- Technical Skills Section -->
        <div class="section technical-skills">
            <h3>Technical Skills</h3>
            <div>
                <h4>Network</h4>
                <ul>
                    <li>Troubleshooting International Enterprise Customers technical problems of L2VPN, L3VPN & Internet Connections.</li>
                    <li>Troubleshooting PE-CE Routing (BGP, OSPF, RIP, STATIC).</li>
                    <li>Dealing with Cisco Routers & Switches and Juniper Routers.</li>
                    <li>Solving the Customer Problems (Connection Down, Instability, Delay, and Packet Loss).</li>
                </ul>
                <h4>Windows Server</h4>
                <ul>
                    <li>Windows Server Administration: Active Directory, Group Policy, and server management.</li>
                    <li>Networking: DNS, DHCP, IP addressing, and network troubleshooting.</li>
                    <li>Virtualization: Hyper-V, VM deployment, and virtual networking.</li>
                    <li>Storage Management: SAN/NAS, RAID, and disk management.</li>
                    <li>Security: User access control, MFA, and network security.</li>
                    <li>Backup & Recovery: Backup solutions and disaster recovery planning.</li>
                    <li>Scripting: PowerShell automation and task scripting.</li>
                    <li>Database Management: SQL Server installation and performance tuning.</li>
                </ul>
                <h4>Linux</h4>
                <ul>
                    <li>Understand the Linux operating system.</li>
                    <li>Have demonstrated the ability to navigate a Linux system.</li>
                    <li>Can execute the power of the Linux command line.</li>
                    <li>Possess knowledge of Linux security and file permissions.</li>
                </ul>
            </div>
        </div>

        <!-- Experience Section -->
        <div class="section experience">
            <h3>Experience</h3>
            <p>
                +1-year experience in CCTV systems, IP camera systems, HD camera systems, security systems, attendance and departure systems, and Cisco VOIP Systems (2024-2025).
            </p>
        </div>

        <!-- Projects Section -->
        <div class="section projects">
            <h3>Projects</h3>
            <ul>
                <li>Company networks implement routing protocols & LAN switching.</li>
                <li>Installed and configured Windows Server 2019 on physical and virtual machines.</li>
                <li>Set up Active Directory Domain Services (AD DS), including user/group management and Group Policy.</li>
                <li>Configured DNS, DHCP, and file/print services.</li>
                <li>Implemented Hyper-V for virtualization and deployed a backup/disaster recovery solution.</li>
                <li>Configuration Central VOIP inside a factory and connected more than one phone.</li>
            </ul>
        </div>

        <!-- Training and Certificates Section -->
        <div class="section training-certificates">
            <h3>Training and Certificates</h3>
            <ul>
                <li>Track Networking CCNAv7 - Introduction to Networks, Switching, Routing, and Wireless Essentials, Networking, Security, and Automation.</li>
                <li>Microsoft System Administration (MCSA).</li>
                <li>NDG Linux Essentials course in the Cisco Networking Academy.</li>
            </ul>
        </div>

        <!-- Soft Skills Section -->
        <div class="section soft-skills">
            <h3>Soft Skills</h3>
            <ul class="skills">
                <li>Microsoft Office 365 skills</li>
                <li>Teamwork and leadership</li>
                <li>Research abilities and self-learning</li>
                <li>Communication Skills</li>
                <li>Time Management</li>
                <li>Work under pressure</li>
                <li>Python programming</li>
                <li>HTML & CSS</li>
            </ul>
        </div>
    </div>
</body>
</html>