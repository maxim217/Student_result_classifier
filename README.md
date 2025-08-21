# Student_result_classifier
def predict_result(study_hours, attendance, assignments):
    if study_hours < 3 and assignments == "No":
        return "Fail"
    elif attendance == "Low" and study_hours < 5:
        return "Fail"
    else:
        return "Pass"
