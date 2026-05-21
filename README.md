# LINKGUARDIAN LITE – Lightweight Offline URL Monitoring Toolkit v1.2.0

LINKGUARDIAN LITE v1.2.0 is a lightweight desktop application designed for fast offline URL extraction, broken link detection, and domain-level analysis from TXT and HTML files. It helps developers, researchers, students, SEO professionals, and content managers quickly validate large collections of links using a clean modern desktop interface.

Built as a lightweight professional UI edition inspired by the PRO workflow, LINKGUARDIAN LITE focuses on simplicity, speed, stability, and low system resource usage while remaining fully beginner-friendly.

------------------------------------------------------------
WINDOWS DOWNLOAD (EXE)
------------------------------------------------------------

Download the latest Windows executable from GitHub Releases:

https://github.com/rogers-cyber/LINKGUARDIAN-LITE/releases

- No Python installation required
- Standalone Windows executable
- Lightweight desktop workflow
- Fast URL validation engine
- Drag & drop support included
- Modern professional interface

------------------------------------------------------------
DISTRIBUTION
------------------------------------------------------------

LINKGUARDIAN LITE is distributed as a lightweight desktop utility.

This repository/documentation may include:

- Python source code
- Windows executable builds
- Commercial upgrade references

Python is only required for running the source code version.

------------------------------------------------------------
FEATURES
------------------------------------------------------------

CORE CAPABILITIES

- 🌐 Extract URLs from TXT and HTML files
- ⚡ Fast lightweight link validation engine
- ❌ Detect broken and unreachable links
- 📊 Domain grouping and analytics
- 🗂 Recursive folder scanning
- 🖱 Drag & drop file support
- 📈 Live progress tracking
- 🧠 Duplicate link filtering
- 💾 CSV export support
- 📦 JSON export support
- 📝 Live activity log console
- 💻 Lightweight modern desktop interface

SUPPORTED FILE FORMATS

- TXT
- HTML
- HTM

SCAN ENGINE

- URL extraction using regex scanning
- Automatic duplicate URL removal
- Real-time HTTP status checking
- Redirect handling support
- Domain statistics tracking
- Broken link counting
- Lightweight request engine using Requests

USER INTERFACE

- Modern ttkbootstrap interface
- Professional dashboard layout
- Drag & drop workflow
- Live status indicators
- Real-time counters
- Progress bar system
- Activity log console
- Minimal learning curve

------------------------------------------------------------
INSTALLATION (SOURCE CODE)
------------------------------------------------------------

1. Clone the repository:

git clone https://github.com/rogers-cyber/LINKGUARDIAN-LITE.git

cd LINKGUARDIAN-LITE

2. Install required dependencies:

pip install requests ttkbootstrap tkinterdnd2

3. Run the application:

python LINKGUARDIAN_LITE.py

------------------------------------------------------------
BUILD WINDOWS EXECUTABLE
------------------------------------------------------------

You can create a standalone Windows executable using PyInstaller.

1. Install PyInstaller:

pip install pyinstaller

2. Build the application:

pyinstaller --onefile --windowed --icon=logo.ico LINKGUARDIAN_LITE.py

The compiled executable will appear in:

dist/LINKGUARDIAN_LITE.exe

------------------------------------------------------------
USAGE GUIDE
------------------------------------------------------------

1. Add Files  
Click "Files" to import TXT or HTML files.

2. Add Folder  
Click "Folder" to scan folders recursively for supported files.

3. Drag & Drop  
Drag files or folders directly into the application window.

4. Start Scan  
Click "START" to begin extracting and validating URLs.

5. Pause or Resume  
Use Pause and Resume controls during long scans.

6. Stop Scan  
Stop scanning instantly using the Stop button.

7. Export Results  
Export scan results as CSV or JSON files.

------------------------------------------------------------
SCAN RESULTS
------------------------------------------------------------

LINKGUARDIAN LITE tracks:

- Total links scanned
- Broken links detected
- Domain statistics
- HTTP response codes
- Failed requests
- Duplicate URL filtering

Each result contains:

- URL
- Status code
- Broken status
- Domain information

------------------------------------------------------------
EXPORT SYSTEM
------------------------------------------------------------

CSV EXPORT

Exports:

- URL
- HTTP status
- Broken state
- Domain name

JSON EXPORT

Exports full structured scan results for:

- Automation workflows
- External analysis
- Reporting systems
- Development pipelines

------------------------------------------------------------
LOGGING & ERROR HANDLING
------------------------------------------------------------

LINKGUARDIAN LITE includes safe error handling:

- Prevents duplicate file imports
- Handles unsupported files safely
- Continues scans after failed requests
- Prevents UI freezing using threading
- Live log monitoring system
- Graceful stop and pause controls
- Safe timeout-based request handling

Application logs are stored in:

~/.linkguardian_lite/lite.log

------------------------------------------------------------
REPOSITORY STRUCTURE
------------------------------------------------------------

LINKGUARDIAN-LITE/

├── LINKGUARDIAN_LITE.py  
├── logo.ico  
├── README.md  
├── LICENSE  

Generated at runtime:

├── Exported CSV reports  
├── Exported JSON reports  
├── lite.log  

------------------------------------------------------------
DEPENDENCIES
------------------------------------------------------------

Python 3.10+

Libraries used:

- requests
- ttkbootstrap
- tkinter
- pathlib
- threading
- queue
- logging
- urllib.parse
- webbrowser

Optional:

- tkinterdnd2 (drag & drop support)

------------------------------------------------------------
INTENDED USE
------------------------------------------------------------

LINKGUARDIAN LITE is ideal for:

- Broken link detection
- Website migration validation
- SEO link auditing
- Content cleanup workflows
- HTML archive inspection
- Research data validation
- Offline URL extraction
- Educational and development workflows

Optimized for speed, simplicity, and lightweight desktop performance.

------------------------------------------------------------
UPGRADE TO PRO
------------------------------------------------------------

Upgrade to LINKGUARDIAN PRO for advanced monitoring and enterprise workflow features:

- Multi-threaded scan engine
- Advanced URL intelligence
- Redirect chain analysis
- PDF reporting system
- Scheduled monitoring
- Advanced filtering rules
- Real-time monitoring dashboards
- Bulk automation workflows
- Export analytics reports
- Enterprise-scale link validation

Website:

https://matetools.gumroad.com

------------------------------------------------------------
ABOUT
------------------------------------------------------------

LINKGUARDIAN LITE is developed by Mate Technologies, focused on building professional offline desktop tools for productivity, monitoring, automation, and developer workflows.

Website:

https://matetools.gumroad.com

© 2026 Mate Technologies  
All rights reserved.

------------------------------------------------------------
LICENSE
------------------------------------------------------------

LINKGUARDIAN LITE is distributed as commercial software.

License terms:

- Personal and commercial usage allowed
- Redistribution or resale as a competing product is prohibited
- Repackaging or rebranding for resale is prohibited
- Source modifications allowed for internal/private use
- Compiled executable usage permitted under license

For commercial licensing or enterprise deployment, contact the developer.

## 📷 Preview

<img alt="LINKGUARDIAN-LITE" src="https://github.com/rogers-cyber/LINKGUARDIAN-LITE/blob/main/LINKGUARDIANLITE%20-%20Main%20Interface.png" />

<img alt="LINKGUARDIAN-LITE" src="https://github.com/rogers-cyber/LINKGUARDIAN-LITE/blob/main/LINKGUARDIANLITE%20-%20Preview%20Scan%20Result.png" />
