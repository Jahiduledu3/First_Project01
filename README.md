# First_Project01
# Assingn the dictionary value

student_scores = {
	'Harry': 81,
	'Ron': 78,
	'Hermione': 99,
	'Draco': 74,
	'Neville': 62,
}

student_grade = {}

for student in student_scores:
	scores = student_scores[student]
	if scores > 90:
		student_grade[student] = 'Outstanding'
	elif scores > 80:
		student_grade[student] = 'Exceeds Expectations'
	elif scores > 70:
		student_grade[student] = 'Acceptable'
	else:
		student_grade[student] = 'Fail'

print(student_grade)