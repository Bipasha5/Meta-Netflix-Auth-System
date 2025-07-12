Meta-Learning Based Netflix Profile Authentication


META LEARNING: 
Adaptive profile authentication and behavioural anomaly detection in streaming services.

This project is all about making streaming profiles — like those on Netflix — more secure and personalized. You know how sometimes someone accidentally clicks into your profile and messes up your watchlist or recommendations? This system is designed to stop that.

It combines dynamic passcodes, behavioral analysis, and meta-learning models to figure out whether the right person is using the profile — and if not, it knows how to react.


What It Does

- Creates one-time passcodes that expire after 60 seconds.
- Tracks how users normally watch content — like what genres they prefer, how much they skip, or what times they usually log in.
- Uses machine learning to detect anything weird or suspicious about how someone is using a profile.
- Pops up a Netflix-style message asking “Are you the respected user?” if something seems off.


Tools & Tech

- Python (Pandas, NumPy, Scikit-learn, PyTorch, TensorFlow)
- Isolation Forest for spotting unusual behavior
- Prototypical Networks for fast learning from user patterns
- Jupyter Notebook + Google Colab for running and testing everything
- HTML & JS for a simple passcode interface



What's in the Dataset

We made a sample dataset of 30 user profiles with:

- Average watch time per session
- Skipped scenes
- Genre preferences
- Login time patterns

Some profiles act normally, while others simulate risky behavior so we could test how the system reacts.


How to Use It

1. Open the notebook in Google Colab
2. Upload the sample dataset CSV files
3. Run the cells — this will:
   - Generate a passcode for the profile
   - Analyze user behavior
   - Detect if it’s suspicious
   - Ask for confirmation if needed
4. View recommendations or lock out intruders


What’s Next

- Add face/fingerprint login for even more security
- Use LSTM models to track behavior over time
- Monitor across multiple devices and locations
- Maybe even voice authentication?



Made By

Bipasha Reddy — for an M.Sc. in Data Science research project at SIES College, Mumbai.  
With guidance from Dr. Abuzar Ansari.


License

MIT — you're free to use, modify, and share this project. Just give credit.


