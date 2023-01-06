# PersonalPortfolio
<!--created using HTML,CSS-->

<!--HTML-->

<!DOCTYPE html>
<html lang="en">
  
<head>
  <style>
img {
  border: 2px solid #ddd;
  width: 150px;
}
</style>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" 
          content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="resume.css">
  <style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
</style>
</head>
  
<body>
    <div class="full">
        <div class="left">    
           <div class="image">
                <img src=
"data:image/jpeg;base64,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" 
                     alt="pic-harshu"
                     style="width:150px;height:150px;">
            </div>
            <div class="Personal info">
                <h2>Personal info</h2><br>
                <p><b>Email:</b>harshadatalele269@gmail.com</p>
                <p><b>Mobile:</b>9137972151</p>
              <p><b>Linkedin Profile:</b><br><a href="www.linkedin.com/in/harshada-talele-b1a0851aa">www.linkedin.com/in/harshada-talele-b1a0851aa</a></p>
            </div>
          <br><br><br>
            <div class="Skills">
                <h2>Skills</h2>
              <ul type="circle">  
               <li><b>Java </b</li>
               <li><b>Python</b</li>
                  <li><b>HTML5</b></li>
                    <li><b>CSS3</b></li>
                 <li><b>SQL</b></li>
                    <li><b>Salesforce</b></li>
                </ul>
            </div>
            <div class="Language">
                <h2>Language</h2>
                  <ul type="circle"> 
                    <li>English</li>
                    <li>Hindi</li>
                  <li>Marathi</li>
                </ul>
            </div>
            <div class="Hobbies">
                <h2>Hobbies</h2>
                 <ul type="circle"> 
                    <li>Kathak Dance</li>
                    <li>Listening Music</li>
                </ul>
            </div>
        </div>
        <div class="right">
            <div class="name">
              <h1>Harshada Lakhichand Talele</h1>
            </div>
           <br>
    
            <div class="Objective">
                <h2>Professional Objective</h2>
                <p>To work in an organization that encourages me to improve my skills and explore my potential while contributing to the growth of the company.
                </p>
            </div>
          <br>
            <div class="Internship">
                 <ul type="circle">
                   <h3><b>Internship</b></h3>
                     <!-- <li> tag is for listing items -->
                   <li><h4>Web Devlopement(Internship studio)</h4></li>
                <p>(July-2020 to Sept-2020)</p>
              <br>
                   <h3><b>Training </b></h3>
                   <li><h4>Cognizant Technology Pvt Ltd</h4></li>
                   <p>(Feb-2022 to May-2022)</p>
                 </ul>
            </div>
          <br>
            <div class="Education">
                <h2>Education</h2>
                <table style="width:100%">
                    <tr>
                        <th>University/college  </th>
                        <th>Passing year </th>
                        <th>percentage/cgpa</th>
                    </tr>
                    <tr>
                        <td>K.Narkhede Vidyalaya,Bhusawal</td>
                        <td>2016</td>
                        <td>89.20%</td>
                    </tr>
                  
                    <tr>
                        <td>K.Narkhede Vidyalaya,Bhusawal</td>
                        <td>2018</td>
                        <td>79.54%</td>
                    </tr>
                  <br>
                  <tr>
                     <td>JSPM Rajarshi Shahu College of Engineering, Pune</td>
                        <td>2022</td>
                        <td>8.62 CGPA</td>
                    </tr>
                </table>
            </div>
            <div class="project">
              <h2><b>Projects </b></h2>
               
                    <ul type="circle">
                    <li>
   <p>Cab Booking System</p> 
                     <ul type="square">
                       <li>Technologies used: <i>Java,JDBC,Swing</i>  </li>
                        <br>
                       <ul type="circle">
                    <li>
   <p>E-commerce website </p> 
                     <ul type="square">
                       <li>Technologies used: <i> HTML,CSS,JS </i></li>
                       <br>
                       <ul type="circle">
                    <li>
                      <p> Recruitment management app </p>
                     <ul type="square">
                       <li>Technologies used: <i>Salesforce(Admin) </i></li>
                       <br>
                      <div class="Cerificates">
              <h2><b>Certificates</b></h2>
                        <ul type="circle">
                    <li>
           <p>Python Programming course| Subhash Programming classes</p> </li>
                          
       <li> <p>Salesforce Course (Admin)</p> </li>    
                    
                          <br>
                          <div class="Position of Responsibility ">
              <h2><b>Position of Responsibility </b></h2>
               
                    <ul type="circle">
                    <li>
                      <p><i>Event Head</i> in Tree Plantation event in RSCOE</p> </li>
                    <li><ul type="circle">
                      <p> <i>Student Coordinator</i> for the event ‘Electric Safety Week', RSCOE</p></li>                  
                    </li>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</body>
  
</html>
                      
                      ----------------------------------------------------------
                      <!-- CSS Code -->
   /* CSS files */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background-color: rgb(253, 254, 255);
    display: flex;
    justify-content: center;
    align-items: center;
}
.full {
    width: 50%;
    max-width: 1000px;
    min-height: 100px;
    background-color:  rgb(245, 239, 231);
    margin: 0px;
    display: grid;
    grid-template-columns: 2fr 4fr;
}
.left {
    position: initial;
    background-color:  rgb(126, 219, 231);
    padding: 20px;
  
}
.right {
    position: initial;
    background-color:   rgb(162, 202, 206);
    padding: 20px;
  
}
.image, .Contact, .Skills, .Language, .Hobbies, .title, 
.Summary, .Experience, .Education, .project {
    margin-bottom: 30px;
}
.h2 {
    background-color: rgb(162, 202, 206);
}




