# SIEM-AND-XDR-USING-WAZUH
Hi, this is a SIEM and XDR simulation using Wazuh Agent & Manager on Windows & Linux VMs
-
First, we run some code in the linux shell to get wazuh manager
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/a000789b-22c3-4a5e-a733-2beb94041362" />
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/fddc359c-8772-4929-9a7c-cbef1b1dc018" />
We can then see the wazuh manager on our screen
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/8bb664a0-4d14-4a4d-aab6-c5b6a62c4fee" />
We then install wazuh agent on windows
<img width="1280" height="832" alt="Screenshot 2025-09-25 at 2 11 20 PM" src="https://github.com/user-attachments/assets/761c57c3-9176-4c47-b2e0-9466a25baaa1" />
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/8c97f099-f378-439e-9ff3-5055892fd011" />
You can see the windows agent on the wazuh manager
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/cd1d969e-b8a1-4b26-9908-c488cd3c8019" />
Okay lets do file integrity monitoring; lets go to the config file & add a folder to monitor
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/fdf5b738-b9a1-4e96-8174-7105cbe7f4a9" />
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/b049c725-9af2-4504-92f4-66a6402b93c6" />
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/06492f94-c434-472a-b4f3-3a5db8697dc0" />
Typing in some text to the file
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/946a9b94-b7fc-4cc2-aae5-26d3b662fe2a" />
I get this on the wazuh manager
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/f6aaaf2a-5e3a-410b-afaf-c7d00b0c2086" />
Now i delete the file & see what happens
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/624acfc5-bb8a-419b-b828-21e665fee4ec" />
There you go
<img width="1280" height="832" alt="image" src="https://github.com/user-attachments/assets/9ae81c38-3c0c-4342-9369-493623eec6ac" />













