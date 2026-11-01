# Gurukripa Enterprises Website — Source Reconstruction

This is a **reconstructed editable source package** based on the frozen website structure and features. It is **not a byte-for-byte export of Vercel's deployed source**, because the Vercel source retrieval interface truncated the larger files. The live deployment was not modified.

Includes homepage with embedded RCS SMS preview, Products, About, Contact, Privacy, Terms and Communication Preferences pages. No Name/Email/Mobile callback form is included (it was undone).

To preview locally: `python -m http.server 8000` from this folder and open http://localhost:8000.

To edit, change the HTML/CSS/JS files. Run `python build.py` only if you want to regenerate HTML files (this overwrites them). RCS SMS is a frontend-only demo; no messaging API is connected.
