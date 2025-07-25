# task-2-windows-firewall
Windows Firewall Configuration and Testing

## Objective  
To configure Windows Defender Firewall rules to block and allow specific program access, and verify the functionality through testing.

## Steps Performed

### 1. Opened Windows Defender Firewall
- Used `wf.msc` to access **Windows Defender Firewall with Advanced Security**.

### 2. Created an Outbound Rule
- Targeted Program: `chrome.exe` (Google Chrome).
- Rule Type: **Outbound Rule**
- Action: **Block the connection**
- Applied to: Domain, Private, and Public profiles.
- Rule Name: `Block Chrome Internet Access`

### 3. Tested the Rule
- Opened Chrome and attempted to browse to a website.
- Result: **Access was blocked**, showing a browser error.

### 4. Disabled the Rule
- Right-clicked the rule and selected **Disable Rule**.
- Chrome successfully accessed the internet again.

## Screenshots Included
- `firewall_rule_created.png` – New rule created in Firewall.
- `chrome_blocked.png` – Chrome showing internet access blocked.
- `rule_disabled.png` – Rule disabled to restore connectivity.

## Conclusion  
Successfully created and tested a Windows Firewall rule. Blocking outbound connections worked as expected, and disabling the rule restored internet access.

## Author  
Naledi Letlalo
