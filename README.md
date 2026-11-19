# NETWORKWALKS-B084-2YU-WK3-PENATRATION-TESTING-REPORT
A practical lab exploring how password-protected PDFs can be unlocked using John the Ripper (CLI and its Johnny GUI) alongside Networkwalks’ browser-based Hash Calculator and Password Cracker — illustrating hash extraction, offline cracking, and why robust passwords matter.

# Recovering a PDF Password — JTR (John & Johnny) and Networkwalks Hash Tools

## Summary
This repo captures a practical exercise in password recovery, carried out on a
password-locked PDF file. The purpose was to see firsthand how password
hashing works, how cracking tools exploit weak passwords, and why password
strength matters in real-world security.

Two methods were explored:
1. **John the Ripper (JTR)**, run through the command line and its GUI
   companion **Johnny**, on a local Windows machine.
2. **Networkwalks' Hash Calculator and Password Cracker**, a pair of
   browser-based tools that pull the hash from a PDF and attempt to crack it
   without any local setup.

This exercise was carried out during a cybersecurity internship at
Networkwalks IT Solutions & Training (Oct–Nov 2026).

## Important Note
The file used here (`My Locked
