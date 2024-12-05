Port Scanner with Vulnerability Check
📖 About
This is a Python script for scanning common network ports and identifying known vulnerabilities associated with them. The tool uses multithreading for efficiency and provides a clear output with colored indicators for open ports.

🚀 Features
Scans commonly used ports (e.g., 21, 22, 80, 443, etc.).
Identifies known vulnerabilities related to open ports.
Multithreaded scanning for faster results.
Colored output for better visibility (green for open ports).
🛠️ Requirements
Python 3.7+
Required Python libraries:
termcolor for colored output.
Install the required library using:

bash
Copiar código
pip install termcolor
📂 Usage
Clone this repository:
bash
Copiar código
git clone https://github.com/<your-username>/<your-repo-name>.git
Navigate to the project directory:
bash
Copiar código
cd <your-repo-name>
Run the script:
bash
Copiar código
python port_scanner.py
Enter the target IP or domain when prompted.
📜 Example Output
plaintext
Copiar código
Digite o endereço IP ou domínio a ser escaneado: 192.168.1.1

Iniciando scan...
[FECHADA] Porta 21
[ABERTA] Porta 22: SSH - Força bruta
[FECHADA] Porta 23
[ABERTA] Porta 80: HTTP - Vulnerabilidades XSS

Scan finalizado.
🧩 How It Works
The script takes an IP or domain as input.
It scans a predefined list of common ports.
If a port is open, it checks for known vulnerabilities and displays them.
The output is color-coded for better readability.
📌 Future Enhancements
Add support for custom port ranges.
Integrate with external databases for real-time vulnerability updates.
Add logging and export options for scan results.
🖥️ Contributions
Contributions are welcome! Feel free to fork this repository, make your changes, and submit a pull request.

🛡️ Disclaimer
This tool is for educational purposes only. Unauthorized scanning of networks is illegal. Use this tool only on networks you own or have permission to test.

