# DigiSonic Media website
Static site (no build step).

## Deploy on Vercel
1. Unzip, push the folder to a GitHub repo (or drag the folder into vercel.com/new).
2. Framework preset: "Other". Build command: none. Output directory: leave blank (root).
3. Deploy.

## EmailJS
Credentials are at the top of the <script> block in index.html.
In EmailJS, add your Vercel domain under Account > Security if you restrict domains.
Template variables: {{from_name}}, {{from_email}}, {{message}}, {{subject}}.
