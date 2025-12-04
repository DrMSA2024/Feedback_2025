markdown
# Student Feedback System - Jamia Hamdard

A web-based student feedback form system for Jamia Hamdard University that generates A4-sized printable/PDF feedback forms.

## 🌟 Features

- **Interactive Form**: Easy-to-use interface for students to provide feedback
- **A4 Optimized**: Perfectly formatted for A4 paper printing
- **PDF Export**: Generate PDF files with clean formatting
- **Real-time Preview**: See changes instantly as you fill the form
- **Teacher Evaluation**: 18 attributes rated on a 5-point scale
- **Additional Feedback**: Syllabus coverage and teaching method assessment

## 📋 Prerequisites

- Modern web browser (Chrome, Firefox, Edge, Safari)
- Internet connection (for CDN libraries)
- Printer or PDF reader (for output)

## 🚀 How to Use

### Online Usage
1. Visit the [GitHub Pages link](#) (if deployed)
2. Fill in the teacher and course details
3. Rate each attribute (1-5 scale)
4. Provide additional feedback
5. Click "Print Form" or "Save as PDF"

### Local Usage
1. Download or clone this repository
2. Open `index.html` in your browser
3. Fill the form and generate PDF

## 📁 Project Structure
student-feedback-system/
├── index.html # Main HTML file
├── README.md # This documentation
├── LICENSE # MIT License
├── .gitignore # Git ignore file
└── assets/ # (Optional) for images/CSS/JS

text

## 🛠️ Technologies Used

- **HTML5**: Structure and form elements
- **CSS3**: Styling and A4 page layout
- **JavaScript**: Form logic and interactivity
- **jsPDF**: PDF generation library
- **html2canvas**: HTML to image conversion

## 📄 Form Sections

1. **Teacher & Course Details**
   - Department, Teacher Name, Programme
   - Semester, Year, Course Title

2. **Performance Assessment** (18 attributes)
   - Planning, Punctuality, Teaching Methods
   - Knowledge, Communication, Support
   - Discipline, Role Model, Overall

3. **Additional Feedback**
   - Syllabus coverage percentage
   - Teaching methods assessment

## 🖨️ Printing Instructions

1. Click "Print Form" button
2. Set printer to:
   - Paper Size: A4
   - Orientation: Portrait
   - Margins: Default or Minimum
3. Print or save as PDF

## 🔧 Customization

To customize for your institution:

1. **Change University Name**: Line ~415 in index.html
2. **Modify Attributes**: Update `attributes` array in JavaScript
3. **Adjust Departments**: Edit department input options
4. **Change Colors**: Modify CSS color variables

## 📊 Attributes Evaluated

1. Planning of the classes
2. Punctuality
3. Promptness in conducting classes
4. Use of audio visual aids
5. Clarity in presentation
6. Depth of course content
7. Knowledge base of teacher
8. Method of communication
9. Recommends additional learning resources
10. Provides feedback to students
11. Encourages co-curricular activities
12. Encourages extracurricular activities
13. Provides assistance and counselling
14. Discusses career goal and placement
15. Interacts with students
16. Maintains discipline in class
17. Inspires as a role model
18. Overall assessment

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Jamia Hamdard University
- jsPDF and html2canvas libraries
- All contributors and testers

## 📞 Support

For issues or questions:
- Open an [Issue](../../issues) on GitHub
- Contact: [Your Email/Contact]

