# WebTech
Hello World
Now Done!
Changed
Again changed (GLOBAL)
Again changed (LOCAL)
changes for branch

আজকে তুমি Git & GitHub নিয়ে যা যা শিখেছো এবং করেছো — তার একটা clear summary নিচে দিলাম 👇

🧠 📚 আজকের Git & GitHub Summary
🟢 1. Git clone & project setup
তুমি repo clone করেছো:
git clone <repo-url>
cd WebTech

👉 Local machine-এ GitHub project আনা

🟢 2. Basic Git workflow শিখেছো
git add .
git commit -m "message"
git push origin main

👉 Local changes → GitHub এ পাঠানো (push)

🟢 3. Git pull শিখেছো
git pull origin main

👉 GitHub-এর changes → local এ আনা

🟢 4. .gitignore concept

তুমি শিখেছো:

.env কী
.gitignore কী

Example:

.env
node_modules/

👉 Sensitive files GitHub এ না পাঠানো

🟢 5. Local vs Global concept
Local config → শুধু current repo
Global config → সব repo

Example:

git config --global user.name "Name"
🟢 6. Push vs Pull
Command	Meaning
push	Local → GitHub
pull	GitHub → Local
🟢 7. Conflict situation শিখেছো 🔥

তুমি শিখেছো:

<<<<<<< HEAD
LOCAL
=======
REMOTE
>>>>>>> commit-id

👉 Conflict কেন হয়:

same file
different changes
sync mismatch
🟢 8. Conflict resolve শিখেছো

তুমি শিখেছো:

✔ Keep local (ours)
git checkout --ours file
✔ Keep remote (theirs)
git checkout --theirs file
✔ Both manually
file edit করে merge
🟢 9. Reset / pull / fetch শিখেছো
git fetch
git pull
git reset --hard origin/main

👉 GitHub sync control করা

🟢 10. Branch & Pull Request শিখেছো 🔥
git checkout -b feature-branch
git push origin feature-branch

👉 তারপর GitHub এ:

Compare & Pull Request
Merge Pull Request
🟢 11. GitHub PR concept

তুমি শিখেছো:

PR = change propose করা
Merge = main branch এ add করা
Conflict = manual fix লাগবে
🎯 Overall Today You Learned

✔ Git basic workflow
✔ Push/Pull system
✔ .gitignore & .env
✔ Local vs Global config
✔ Merge conflict handling
✔ Conflict resolve (ours/theirs/both)
✔ Branching
✔ Pull Request & Merge process

🚀 Final summary (one line)

👉 আজকে তুমি GitHub workflow full lifecycle (clone → edit → push → pull → conflict → branch → PR → merge) শিখে ফেলেছো
