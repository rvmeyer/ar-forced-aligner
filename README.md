# ar-forced-aligner
Forced alignment for dialectal Arabic

This repository contains three forced alignment models. 

Model 1: Full consonant set, reduced vowel set. Best alignment performance.
Model 2: Full consonant set, full vowel set.
Model 3: Reduced consonant set, full vowel set.

Full <a href = "https://aclanthology.org/L18-1574.pdf">CAPHI</a> consonant set: b, b., d, d., dh, dh., dj, dz, f, f., g, gh, gy, h, j, k, kh, l, l., m, m., n, n., p, p., q, qh, r, r., s, s., sh, t, t., th, ts, tsh, v, z, z., 2, 3, 7

Reduced set excludes dz, f., gy, m., n., p, p., qh, r., ts, tsh, v

Full glide/vowel set: w, y, aa, ee, ii, oo, uu, a, e, i, o, u

Reduced vowel set excludes mid vowels

<a href = "https://colab.research.google.com/drive/1PwWiKjFJw1pviFrOdWgqR8UZfzi9_wXe?usp=drive_link">Here</a> is a CoLab file for preprocessing text and generating dictionaries (this is what worked for my data, currently undergoing revisions to make it more customizable. Under construction, in disrepair). The same file as a .py is also available.
