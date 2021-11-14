## FitLife

## 💡 Inspiration
Eating a poor quality diet high in junk food is linked to a higher risk of obesity, depression, digestive issues, heart disease and stroke, type 2 diabetes, cancer, and early death. And as you might expect, frequency matters when it comes to the impact of junk food on your health. Eating well helps to reduce the risk of physical health problems like heart disease and diabetes. It also helps with sleeping patterns, energy levels, and your general health.

## 💻 What it does
- Provide a platform for everyone to keep track of the calorie consumed.
- Check if the food you are consuming is safe for your diet.
- Keep track of your workout.
- Find recopies.
- Easy to keep track.
- Personalized exercise recommendation based on your BMI and calories intake
- Calculation of Base melabolic Rate (BMR) to recommend calories intake according to you

## ⚙️ How we built it

- ML: Python, TensorFlow
- Frontend: HTML, CSS, JS
- Backend: Django
- Database: CockroachDB
- Authentication: Auth0

## Use of CockroachDB

- We have used CockroachDB as a primary database because it is an easy-to-use, open-source and indestructible SQL database.

## Use of Linode
We utilized Linode for its hosting and storage. Linode is one of the top IaaS providers and is incredibly easy to use and the free Linode credit from MLH for us to learn and build on Linode was the cherry on the cake! Linode is fast, flexible, and reliable, and we truly enjoyed using it.

## 🧠 Challenges we ran into

- Reducing the size of the trained model was challenging for us. Bigger size meant that users have to wait a long time for obtaining prediction results and we would not be able to upload it on GitHub as well. We researched the ways we can use to reduce the model's size and found Quantization Aware Training to be useful and effective and we are glad it worked.

## 🏅 Accomplishments that we're proud of

- Achieving 95%+ accuracy on ML models.
- Completing all these features in just two days is another.

## 📖 What we learned

- Using Quantization Aware Training to reduce the size of the model
- Integrate ML models directly without creating an API with Django 
- collaboration.

## 🚀 What's next for Fitlife

- Improving the accuracy of the models.
- Adding more features.
