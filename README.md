
# Intelliwise: Interactive Quiz Generator from YouTube Lectures

  

## Description

The Intelliwise is an innovative tool designed to transform passive video learning into an engaging and interactive experience. By leveraging the power of YouTube's educational content, this application allows self-learners to actively test their understanding of material covered in video lectures.

  

### Key Features:

- **Quiz Generation**: Automatically creates quizzes from YouTube lecture transcripts, enabling users to validate their comprehension of the video content.

- **Multiplayer Functionality**: Supports competitive learning through multiplayer quiz sessions, fostering a collaborative and fun learning environment.

- **Leaderboard System**: Displays scores in a leaderboard format, adding a gamified aspect to the learning process and encouraging friendly competition among peers.

  

### How It Works:

1. **URL Input and Validation**: Users can input a YouTube video URL, which is validated and processed to retrieve captions.

2. **Caption Processing**: The system uses language detection and translation to ensure quizzes can be generated from videos in various languages.

3. **GPT API Interaction**: Employs GPT-4's powerful capabilities to design prompts and generate quiz questions that are contextually relevant to the lecture content.

4. **Iterative Design and Testing**: Continuous refinement of prompts ensures high-quality quiz questions that are both challenging and educational.

5. **Quiz Engagement**: Players can scan a QR code to join a quiz session, compete with friends, and see their scores on the leaderboard after quiz completion.

![Quiz Generator Interface](https://i.postimg.cc/qBFvVZRQ/final.png "Interactive Quiz Generator Interface")
  

This tool aims to make education more dynamic, accessible, and enjoyable for self-learners around the globe. Try it out to reinforce your learning, challenge your friends, and have fun while you learn!

  

We believe in the power of collaborative learning and open-source development. If you're passionate about education technology and would like to contribute to the project, we welcome your ideas and contributions!

## What Intelliwise does?

In an era where self-education and online resources are more prevalent than ever, BlackMarker aims to bridge the gap between learning and testing. Our platform addresses the challenges self-learners face such as the lack of interactive tools and means to assess their knowledge after consuming educational content. BlackMarker enhances the learning journey by converting static YouTube video lectures into interactive, engaging quizzes. It streamlines the quiz creation process, centralizes learner data for personalized insights, and implements a leaderboard system to add a competitive edge to education. By utilizing GPT-powered AI, robust data analytics, and secure communication protocols, BlackMarker protects user data while offering a seamless and collaborative learning environment. 

### How we built Intelliwise?

The creation of BlackMarker is the culmination of collaborative efforts from experts in the fields of education, technology, and design. We conducted extensive research to pinpoint the difficulties faced by self-learners and set out to solve them using innovative technology. The frontend was developed with React, enabling a dynamic and responsive user experience. The backend was built on Node.js, ensuring efficient processing and scalability. BlackMarker is a testament to our commitment to providing a robust and intuitive educational tool.

### Challenges we ran into with Intelliwise?

Throughout the development, we encountered and surmounted several challenges. Our journey was marked by intricate backend data processing issues and the integration of AI to provide contextually relevant and accurate quiz questions. Our team's dedication and perseverance led us to develop novel solutions that seamlessly blend AI intelligence with educational content to ensure BlackMarker meets the diverse needs of learners.

### Accomplishments we're proud of with Intelliwise?

We take immense pride in our triumphs with BlackMarker, especially overcoming the complexities inherent in personalized education technology. We have crafted a platform that not only quizzes but adapts and responds to individual learning patterns. This accomplishment is a step forward in transforming the landscape of digital education and making personalized learning accessible to all.

### What we learned from building Intelliwise?

The development of BlackMarker has been a profound learning experience. It has enhanced our expertise in AI, taught us the nuances of data handling in education, and underscored the importance of a user-centric approach in technology. Above all, it has shown us the potential of combining AI with education to craft personalized learning experiences.

### What's next for Intelliwise?

Moving forward, BlackMarker is set to expand its horizons. We plan to refine our AI algorithms for more nuanced personalization, widen our content spectrum to encompass diverse educational fields, and enhance user interface design for an even more intuitive experience. The roadmap includes integrating with additional platforms and exploring new technologies to keep BlackMarker at the forefront of educational innovation.


  ## Authors

- [@iamshivakhatri](https://github.com/iamshivakhatri)

- [@miyannishar](https://github.com/miyannishar)

- [@sajanpoudel](https://github.com/sajanpoudel)

- [@aayush-jpg](https://github.com/Aayush-jpg)

## Appendix  
For further reference and detailed documentation on the APIs used within this project, please consult the following resources: -  

**YouTube Transcript API**
To learn more about how to retrieve video captions from YouTube, refer to the [YouTube Transcript API Documentation](https://developers.google.com/youtube/v3/getting-started).

**OpenAI GPT API** 
For information on how to use OpenAI's GPT API for generating quiz questions, visit the [OpenAI API Documentation](https://beta.openai.com/docs/).

## License

[MIT](https://choosealicense.com/licenses/mit/)



## Frequently Asked Questions (FAQ)

### How does the quiz generator work?
The quiz generator extracts captions from a provided YouTube lecture video using the YouTube Transcript API, then processes this text to create relevant quiz questions through interactions with the GPT API. The questions are formatted into a quiz which can be accessed via a QR code.

### Can I generate quizzes from any YouTube video?
The tool is optimized for educational content and works best with clear, well-articulated lectures. While it might work with other types of videos, the quality and relevance of the quiz questions may vary.

### What languages does the quiz generator support?
The quiz generator supports multiple languages, as it is capable of language detection and translation to process video captions from different languages into quiz questions.

### How many players can join a quiz?
There's no fixed limit to the number of players that can join a quiz. However, the optimal number may depend on the server capacity and your specific implementation.

### How is the leaderboard score calculated?
The leaderboard score is calculated based on the number of correct answers and the time taken to complete the quiz. The exact scoring algorithm can be adjusted to suit different types of quizzes.

### Can I contribute to the development of this project?
Yes, contributions are welcome! You can contribute by forking the repository, making changes, and submitting a pull request. Please see the 'Contribution' section for more details.

### Is there a mobile app version?
Currently, the quiz generator is a web-based application, but plans for a mobile version may be considered in the future based on user feedback and demand.

### Who do I contact for support or feedback?
You can raise an issue on the GitHub repository for support or suggestions. We strive to respond to all queries in a timely manner.

For more detailed questions or inquiries, you can also reach out to us via the contact information provided in the repository.

---

We hope these FAQs help you get started with our Interactive Quiz Generator. For any other questions, don't hesitate to open an issue in the GitHub repository.


  

---

  

Join us in revolutionizing online learning, one quiz at a time!
