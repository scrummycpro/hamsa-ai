Forking the Ollama RAG Repository

Forking a repository allows you to create a copy of the original project under your GitHub account. This lets you experiment, customize, or contribute changes without affecting the original repository.

Steps to Fork the Repository

	1.	Navigate to the Repository:
	•	Go to the Ollama RAG repository: scrummycpro/ollama-rag.
	2.	Click the Fork Button:
	•	On the top right of the repository page, click the Fork button.
	•	GitHub will prompt you to choose an account where the fork will reside (use your GitHub account).
	3.	Wait for Fork Creation:
	•	After clicking Fork, GitHub creates a copy of the repository under your account. You will now have your own copy of ollama-rag.

Cloning Your Fork

After forking, clone your repository to your local machine for development.
	1.	Copy the clone URL for your forked repository (e.g., https://github.com/<your-username>/ollama-rag.git).
	2.	Clone the repository:

git clone https://github.com/<your-username>/ollama-rag.git
cd ollama-rag

Syncing with the Original Repository

If the original repository gets updated, you can sync your fork to pull in the changes.
	1.	Add the original repository as a remote:

git remote add upstream https://github.com/scrummycpro/ollama-rag.git


	2.	Fetch the latest changes from the original repository:

git fetch upstream


	3.	Merge the changes into your local copy:

git merge upstream/main


	4.	Push the merged changes to your fork:

git push origin main

Making Contributions

If you’d like to contribute changes to the original repository, you can submit a pull request.
	1.	Make Changes:
	•	Modify the code in your fork as needed.
	•	Commit the changes:

git add .
git commit -m "Describe your changes here"
git push origin main


	2.	Create a Pull Request:
	•	Navigate to the original repository on GitHub.
	•	Click Pull requests → New pull request.
	•	Choose your fork as the source and the original repository as the destination.
	•	Submit the pull request with a description of your changes.
	3.	Collaborate:
	•	The repository maintainer will review your changes and merge them if approved.

Benefits of Forking

	•	Experimentation: Safely test changes in your own repository without affecting the original.
	•	Customization: Tailor the project to your needs.
	•	Collaboration: Contribute to the original repository by submitting pull requests.
	•	Backup: Keep your own copy of the repository, even if the original gets deleted.

Let me know if you’d like assistance setting up the repository or making your first contribution! 🚀