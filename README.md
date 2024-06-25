# audAIence

audAIence is an innovative AI-powered classroom engagement platform developed by Rishiraj Acharya & Piyush Thakur for the Gemini API Developer Competition. It modernizes and digitalizes the brilliant concept introduced by education expert Dylan Wiliam, enhancing real-time student-teacher interaction in both physical and virtual classrooms.

## Inspiration

The project is based on Dylan Wiliam's ingenious idea of using colored cups to gauge student understanding in real-time. In his original concept, students use green, orange, and red cups to indicate their level of comprehension during a lesson. You can learn more about his idea [here](https://www.youtube.com/watch?v=lX0JEZ3Pgk4&t=24s).

## What audAIence Does

audAIence takes this concept to the next level by:

1. Providing a digital interface for students to indicate their understanding level.
2. Allowing students to ask questions in real-time.
3. Utilizing AI to provide instant answers to student questions based on the lecture material.
4. Giving teachers a comprehensive dashboard to monitor student engagement and address concerns promptly.

## Key Features

- Real-time student engagement tracking
- AI-powered question answering system
- Interactive teacher dashboard with data visualization
- Seamless integration of slide materials
- Support for both in-person and remote learning environments

## Setup and Installation

### Prerequisites

- Python 3.7+
- pip
- virtualenv (recommended)

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/audAIence.git
cd audAIence
```

### Step 2: Set Up a Virtual Environment (Optional but Recommended)

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Set Up Environment Variables

Create a `.env` file in the project root and add your Gemini API key:

```
GEMINI_API_KEY=your_api_key_here
```

### Step 5: Run the Application

```bash
python main.py
```

The application will be available at `http://localhost:5000` by default.

## Usage

1. Teachers:
   - Access the teacher interface at `http://yourdomain.com/<class_id>/teacher`
   - Upload lecture slides (PDF format)
   - Monitor student engagement in real-time
   - Address questions and concerns as they arise

2. Students:
   - Join a class by navigating to `http://yourdomain.com/<class_id>`
   - Indicate understanding using color-coded buttons
   - Ask questions that get instant AI-powered responses
   - View answers to their own and classmates' questions

## Impact and Benefits

audAIence aims to revolutionize classroom dynamics by:

- Enhancing student engagement and participation
- Providing immediate feedback to teachers about student comprehension
- Offering instant, AI-powered answers to student questions
- Improving the learning experience for both in-person and remote students
- Helping teachers identify and address learning gaps more efficiently

By digitalizing and enhancing Dylan Wiliam's concept, audAIence makes continuous formative assessment more accessible and effective in modern educational settings.

## Future Enhancements

- Integration with popular learning management systems
- Support for more file formats beyond PDF
- Advanced analytics for long-term student performance tracking
- Mobile app for easier access on smartphones and tablets

## Contributing

We welcome contributions to audAIence! Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Dylan Wiliam for the original concept that inspired this project
- The Gemini API team for providing the AI capabilities
- All the educators and students who provided feedback during the development process
