- 👋 Hi, I’m @Jafirhossain
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Jafirhossain/Jafirhossain is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# my_sieve_func/main.py

@sieve.function(
	name="my_custom_function",
	python_packages=[
		"opencv-python"
	],
	system_packages=[
		"ffmpeg"
	],
	run_commands=[
		"mkdir -p /root/.cache/models/",
	]
)
def my_custom_function(a: int,  b: int) -> int:
	import cv2 # This will be installed in your cloud function and can be imported here

	return a + b
