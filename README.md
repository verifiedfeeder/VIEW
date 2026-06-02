# 🎬 VIEW — Video Intelligence & Extraction Workspace

Welcome to **VIEW**, a high-performance, single-file clinical and media utility engineered to map raw video streams, track diagnostic file headers, and extract target luma-filtered screenshots without data ever leaving your browser. 🚀

---

## ✨ Features

* 📊 **Raw MediaInfo Simulation Engine:** Generates aligned, unparsed textual logs mirroring an exact local binary setup.
* 🔆 **Luma Precision Filtering:** Evaluates frame exposure dynamically to discard blank or under-exposed frames.
* 📦 **Flexible Data Output Controls:**
* 📋 Copy the complete MediaInfo Data Matrix inside protective BBCode tags.
* 📄 Export raw analytics to a clean `.txt` document.
* 🖼️ Download individual screenshots directly from the interface gallery.
* 🤐 Compress all extracted images and text diagnostics together into a unified `.ZIP` archive instantly.



---

## 🛠️ How to Use VIEW

### 1️⃣ Load your Media Asset

* Click on **Choose File** under the **Binary Stream Input Reference** heading.
* Select any local video file (`.mp4`, `.mkv`, `.webm`, etc.). Because processing happens entirely client-side, large files load instantly without server upload delays. ⚡

### 2️⃣ Adjust Extraction Metrics

* **Target Extract Volume:** Define how many random timeline points the pipeline should sample (e.g., `10`).
* **Luma Precision Threshold:** Set the minimum exposure level (`0` to `255`). Frames with an average brightness lower than this value will be automatically filtered out to prevent solid black captures. 📉

### 3️⃣ Run the Pipeline

* Click the **Execute View Pipeline** button. ⚙️
* The tracker will dynamically update as it seeks, renders, and scores frames across the video timeline.

### 4️⃣ Export and Save Your Data

Once processing finishes, choose your preferred export approach:

* 📑 **Copy Data Matrix:** Copies the plain-text MediaInfo schema directly to your clipboard.
* 📝 **Export Plain Text:** Saves the diagnostics text as a `.txt` file named after your video.
* 🖼️ **Download Individual Images:** Click the standalone **Download Image** button located directly beneath any specific image in the gallery.
* 🗜️ **Export All Images & Text as ZIP:** Compiles all accepted screenshots along with the text diagnostic file into a single `.zip` package.

---

## 📁 Project Structure & Tech Stack

This tool runs as a completely self-contained workspace:

* **HTML5 Canvas & Video API:** Handles high-fidelity binary frame seeking and sub-layer pixel processing.
* **JSZip Library:** Utilizes an asynchronous, thread-safe client-side script to bundle items smoothly into ZIP archives without freezing your workspace tabs. 🧊

---

## 🔒 Security & Privacy

> 💡 **Zero-Server Architecture:** All parsing, frame extraction, and compression logic run locally within your browser sandbox. No telemetry data, media files, or file metadata are ever transmitted over the network, ensuring complete data security.
