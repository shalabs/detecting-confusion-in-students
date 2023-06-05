# Motivation

The primary cause of poor performance of students during the learning process is confusion. To make online education more effective, it is important to detect confusion in real-time. While Massive Open Online Courses (MOOCs) cater to a large number of students simultaneously, they have certain drawbacks in comparison to traditional in-class education. Currently, attempts are being made to enhance communication between instructors and students through interactive tools. Pervious works has shown the effectivness of applying bidirectional LSTM on this dataset. I expermint with variations of LSTM as reported in recent works to improve on the current state of the art.

# Dataset Information

The dataset consists of EEG signal data collected from 10 college students while they watched MOOC video clips. The EEG signal can help detecting students mental states by acquiring signals from the brain.These 10 students were assigned to watch 20 videos, 10 of which were pre-labeled as “easy” and 10 as “difficult”. First, several online education videos were selected that were assumed not to be confusing for the students. Each video was about 2 minutes long. For “difficult” videos, the two-minute clip was taken abruptly from the middle of a topic to make the videos more confusing. The dataset was prepared by randomly selecting 5 videos from each category for each student. The dataset has a total of 12811 samples. On an average there are 120 samples for each data points. There are 100 datapoints, 10 coming from each student.

![image](https://github.com/shalabs/detecting-confusion-in-students/assets/80707214/b6735813-0e74-44b5-a40d-2c7d7d352a8b)
