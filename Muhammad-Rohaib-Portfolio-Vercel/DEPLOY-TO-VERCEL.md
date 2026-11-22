# Quick Vercel deployment checklist

- [ ] Extract `Muhammad-Rohaib-Portfolio-Vercel.zip`.
- [ ] Confirm `index.html` and `vercel.json` are at the top level beside `assets/`.
- [ ] Upload the extracted folder contents to the root of a GitHub repository.
- [ ] Import that repository in Vercel.
- [ ] Framework Preset: **Other**.
- [ ] Root Directory: `./`.
- [ ] Build Command: leave empty.
- [ ] Install Command: leave empty.
- [ ] Output Directory: `.`.
- [ ] Deploy and open the production domain.
- [ ] Test Home, Services, Logo Portfolio, Video Portfolio, Web Portfolio and Contact.
- [ ] Submit a test contact form and verify the message arrives in Formspree.

If Vercel shows a 404, the most common cause is a Root Directory setting that points above or below the folder containing `index.html`.
