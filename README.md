# Multi-Platform Matrix Build with Artifacts

This repository demonstrates a GitHub Actions matrix build workflow that:
- Runs in parallel on multiple OS environments (Ubuntu, Windows, macOS)
- Uses different Python versions (3.9, 3.10, 3.11)
- Uploads non-empty build artifacts for every variant

### ✅ Validation Highlights
- At least 3 successful matrix jobs
- Each job uploads a unique artifact prefixed with **build-c5c5b38**
- Includes a step with identifier **matrix-c5c5b38**
- README includes author email

### 👤 Author
**Garima Dahuja**  
📧 garimadhuja@gmail.com
