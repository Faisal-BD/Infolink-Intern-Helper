# Intern Helper 🛰️

A simple, friendly web guide that helps network support interns remember how to do
their daily tasks and in what order. It is a single HTML file with no frameworks,
no build step and no server.

## Features

- **Step-by-step task guides** for Troubleshoot, Find MAC (reverse way), Task Create,
  MAC Configure, ONU Loss, New Connection and more, written in plain language.
- **Diagrams:** an animated Router → OLT → ONU → Client map that lights up the
  devices each task uses, a numbered "big picture" flow, and menu-path chips.
- **Progress ticks:** click a step number to mark it done, with a progress bar.
- **OLT List table:** a scrollable table with a sticky header, search, copy-to-clipboard,
  and add/delete/rename for rows and columns.
- **Admin mode (password protected):** edit the page title, tasks, steps, flows, devices
  and tables. You can also add, delete and reorder tasks.
- **Backup and restore:** copy your data out as text and paste it back in.
- **Light and dark mode** with a toggle, a layout that works on phones, and a task search box.

## Getting started

1. Download `Intern_Helper.html`.
2. Open it in any modern browser, or host it on GitHub Pages, Cloudflare Pages or any static host.

## Using admin mode

Turn on the **Admin** switch in the top bar and enter the password. Once unlocked you can
edit everything. A **🔑 Password** button lets you change the password.

> **Note:** The password is checked in the browser, so it only prevents accidental edits.
> It is not real security. For real protection, host the page behind a proper login.

## Where your data is saved

Edits are saved in your browser's `localStorage`, so they stay on that browser and device only.
Use **Backup** to move your data to another browser.

## Tech

Plain HTML, CSS and JavaScript. No dependencies.

## Author

Made by **Aminur Refat Faisal**, Network Support Engineer-Intern, Infolink Limited.
Email: arfaisal712@gmail.com · WhatsApp: 01711101445
