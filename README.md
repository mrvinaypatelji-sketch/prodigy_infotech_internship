# # Data-structure-task-01
import matplotlib.pyplot as plt

# Sample data
genders = ['Male', 'Female', 'Other']
counts = [50, 40, 10]

# Create bar chart
plt.bar(genders, counts, color=['blue', 'pink', 'green'])
plt.title("Gender Distribution")
plt.xlabel("Gender")
plt.ylabel("Count")
plt.show()
