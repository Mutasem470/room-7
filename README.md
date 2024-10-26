# room-7
: Feature Engineering - Student Performance Prediction

Transform the raw student performance data by creating a
new feature, the Performance Index, which combines HW and
exam scores to better predict student success.

This code computes a Performance Index for each student by multiplying their homework and exam scores, then prints the resulting list.

data = {
    'homework_score': [40, 60, 80],
    'exam_score': [70, 85, 90]
}

# Calculate the Performance Index as the product of homework and exam scores
performance_index = [hw * exam for hw, exam in zip(data['homework_score'], data['exam_score'])]

print(f"Performance Index (Homework * Exam): {performance_index}")
