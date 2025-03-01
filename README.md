<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exploring the Dentistry Career</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-image: url('https://www.shutterstock.com/shutterstock/photos/1914531895/display_1500/stock-vector-dental-services-vector-concept-for-landing-page-dentists-make-x-ray-scan-of-teeth-to-help-1914531895.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 0;
            text-align: center;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        header h1 {
            margin: 0;
            font-size: 3.5em;
            background-color: rgba(0, 0, 0, 0.6);
            display: inline-block;
            padding: 10px 20px;
            border-radius: 10px;
        }
        .content {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 15px;
            text-align: left;
        }
        tr:nth-child(even) {
            background-color: #f9f9f9;
        }
        @media (max-width: 768px) {
            header {
                padding: 100px 0;
            }
            header h1 {
                font-size: 2.5em;
            }
            .content {
                margin: 10px;
                padding: 15px;
            }
        }
    </style>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>

<header>
    <h1>Exploring the Dentistry Career</h1>
</header>

<div class="content" id="introduction">
    <table>
        <tr bgcolor="#f2f2f2">
            <td>
                <h3>Dentistry is a 5-year program focused on the care and treatment of oral health, including subjects like Anatomy and Physiology. Dentists can specialize in areas such as Periodontics, Orthodontics, Pediatric Dentistry, and Maxillofacial Surgery, and work in private practices, public clinics, hospitals, and educational institutions. Personally, I find that this field is exactly what I would like to study because it combines science with the opportunity to help people.</h3>
            </td>
        </tr>
    </table>
 <div style="text-align: center;">
    <p><strong>Why did you choose this career?</strong><br>I chose dentistry because it perfectly matches my interests. When I think about my realistic interests, I enjoy working with my hands and solving practical problems, which is essential in dentistry. My investigative inclination is also reflected, as I have always had a passion for science and continuous learning. Additionally, my conventional interests also play a role in this choice, as dentistry requires following established protocols and procedures, which allows me to work efficiently. I also feel that I prefer this career because it fosters creativity in problem-solving. Furthermore, I enjoy setting goals, and in dentistry, it is essential, allowing me to plan the appropriate treatment for each patient and measure my progress, as well as stay motivated. I like to stimulate my brain, which is important in this career because one must always stay updated with the latest scientific advancements and solve complex problems.</p>
 
<img src="https://www.shutterstock.com/shutterstock/photos/2476800705/display_1500/stock-vector-red-lips-with-braces-on-healthy-smile-mouth-with-orthodontic-apparatus-on-clean-teeth-oral-health-2476800705.jpg" alt="Descripción de la imagen" style="width:50%;height:40%;">


    <p><strong>How would you describe or explain this career to someone unfamiliar with it?</strong><br>Dentistry is the medical specialty that focuses on the health of teeth and gums. Dentists work to prevent, diagnose, and treat oral health issues. They perform dental cleanings, fix cavities, and carry out more complex procedures like surgeries and orthodontics. Additionally, they educate patients on how to maintain their oral hygiene and prevent future problems. It is a profession that combines science and manual skills, requiring precision and good communication abilities to effectively treat patients.</p>

   <a href="https://youtu.be/0CFLTrPvwFY?si=tzyuPROWezN9hUcV">So You Want to Be a DENTIST </a>

    <p><strong>What are some of the skills required to be successful in this career?</strong><br>To be successful in the field of dentistry, it is essential to possess key skills that allow me to provide excellent dental care and maintain a positive relationship with patients. Problem-solving will be a crucial skill because it will allow me to quickly and accurately identify dental issues, developing personalized and effective solutions. Additionally, the ability to innovate will be vital to implement new techniques and methods that improve dental procedures, ensuring efficient and high-quality treatments. Another indispensable skill will be communication. I must be able to clearly explain diagnoses and treatments to my patients, reducing their anxiety and building trust. Creating an atmosphere of trust and comfort will be essential for successful treatment. Moreover, communication skills will facilitate effective interaction with my colleagues and other healthcare professionals, ensuring a comprehensive and coordinated approach to patient care.</p>

<img src="https://www.shutterstock.com/shutterstock/photos/2465047861/display_1500/stock-vector-dentists-treating-tooth-with-stomatology-drilling-machine-stomatologists-care-about-oral-hygiene-2465047861.jpg"  style="width:50%;height:40%;">

    <p><strong>What does a typical day in the life of this career look like?</strong><br>In a typical day, a dentist does a bit of everything: starts by reviewing the agenda and preparing the office, then focuses on seeing patients, performing dental cleanings, diagnosing issues such as cavities and gum diseases, and carrying out procedures like fillings and root canals. Between appointments, they review medical records, answer patients' questions, and coordinate with the administrative team. At the end of the day, they clean and organize everything for the next day. Additionally, they are always learning new things to stay up-to-date with the latest techniques and technologies. This professional lifestyle allows me to maintain a good balance between work and personal life; if I had my own practice, I could manage my time more flexibly. The good income level provides the financial stability needed to enjoy a high quality of life, and helping patients improve their oral health is incredibly rewarding, making me feel good both at work and in my personal life.</p>

    
    <canvas id="dentistChart" width="400" height="200"></canvas>
    <script>
        const ctx = document.getElementById('dentistChart').getContext('2d');
        const dentistChart = new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['Consultas', 'Procedimientos', 'Revisión de Registros', 'Tareas Administrativas', 'Capacitación'],
                datasets: [{
                    label: 'Hours spent',
                    data: [4, 3, 1, 2, 1], 
                    backgroundColor: [
                        'rgba(75, 192, 192, 0.2)',
                        'rgba(54, 162, 235, 0.2)',
                        'rgba(255, 206, 86, 0.2)',
                        'rgba(153, 102, 255, 0.2)',
                        'rgba(255, 99, 132, 0.2)'
                    ],
                    borderColor: [
                        'rgba(75, 192, 192, 1)',
                        'rgba(54, 162, 235, 1)',
                        'rgba(255, 206, 86, 1)',
                        'rgba(153, 102, 255, 1)',
                        'rgba(255, 99, 132, 1)'
                    ],
                    borderWidth: 1
                }]
            },
            options: {
                scales: {
                    y: {
                        beginAtZero: true
                    }
                }
            }
        });
    </script>
</div>

</body>
</html>
