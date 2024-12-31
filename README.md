# fitness-app-data
FittingApp is a mobile application that collects real-world health and fitness tracking data from 3,000 participants over a one-year period. The dataset takes daily activities, vital health measurements, and lifestyle factors and makes them valuable for health analytics and predictive modeling. The application was created within the scope of the 2023 ***Istanbul Kultur University Electrical and Electronics Engineering*** graduation project to create a mobile application, collect data from phones and smart watches, and generate meaningful structures from this data using machine learning methods.

## Features Description
### Demographic Information

- participant_id: Unique identifier for each participant
- age: Age of participant (18-65 years)
- gender: Gender (M/F/Other)
- height_cm: Height in centimeters
- weight_kg: Weight in kilograms
- bmi: Body Mass Index calculated from height and weight

#### Activity Metrics

- activity_type: Type of exercise (Running, Swimming, Cycling, etc.)
- duration_minutes: Length of activity session
- intensity: Exercise intensity (Low/Medium/High)
- calories_burned: Estimated calories burned during activity
- daily_steps: Daily step count

#### Health Indicators

- avg_heart_rate: Average heart rate during activity
- resting_heart_rate: Resting heart rate
- blood_pressure_systolic: Systolic blood pressure
- blood_pressure_diastolic: Diastolic blood pressure
- health_condition: Presence of health conditions
- smoking_status: Smoking history (Never/Former/Current)

#### Lifestyle Metrics

- hours_sleep: Hours of sleep per night
- stress_level: Daily stress level (1-10)
- hydration_level: Daily water intake in liters
- fitness_level: Calculated fitness score based on cumulative activity
- fitness_level_category: The fitness level column has been made categorical by dividing it into 3 equal parts.

The aim of the project is to classify individuals as low, medium and high according to their fitness levels in the light of the data obtained.
