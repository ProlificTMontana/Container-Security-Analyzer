# Container Security Analyzer

A simple frontend interface for visualizing container security scan results.  This project provides a user interface for scanning Docker images for vulnerabilities and misconfigurations, simulating integration with CI pipelines and Slack notifications.

## Features

*   **Docker Image Scanning:**  Simulates scanning Docker images for vulnerabilities and misconfigurations.
*   **CI Pipeline Integration:**  Demonstrates how the analyzer can be integrated into CI pipelines.
*   **Slack Notifications:**  Simulates sending Slack notifications for high and critical vulnerabilities.
*   **Scan Result Comparison:**  Compares scan results across multiple runs to track improvements and regressions.
*   **Theme Toggle:** Supports light and dark themes.

## Usage

1.  Download or clone the `ContainerSec.html` file.
2.  Open the file in your web browser.
3.  Enter a Docker image name in the input field (e.g., `nginx:latest`).
4.  Click the "Run Scan" button to simulate a scan.
5.  View the scan results, including vulnerability counts and a simulated Slack notification (if applicable).

## Notes

*   This project is a frontend demonstration and does not perform actual container security scans.  The scan results are simulated using JavaScript.
*   To implement real container security scanning, you would need to integrate this frontend with a backend service that uses tools like Trivy to perform the scans and send Slack notifications via webhooks.

