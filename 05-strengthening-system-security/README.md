# Strengthening System Security

## Objective

Configure public-key authentication for remote server access
and implement one-time-password authentication on a separate
server.

## Tools and Technologies

- Linux terminal
- Windows PowerShell
- OpenSSH
- RSA SSH key pairs
- OTPW
- Pluggable Authentication Modules (PAM)
- APT package management
- nano text editor
- systemctl

## Summary of Work

I generated SSH key pairs from Linux and Windows environments
and configured public-key authorization on a remote server.
This involved managing public keys and updating the server's
authorized-key configuration for the required client systems.

On a separate server, I installed OTPW and modified PAM and
SSH settings to support one-time-password authentication.
I also generated an OTPW password list and restarted the
SSH service to apply the configuration changes.

During the exercise, I checked key-generation and installation
messages, reviewed configuration changes, and confirmed
creation of the password-list file.

## Skills Practiced

- Generating SSH key pairs
- Managing public-key authorization
- Configuring remote access across Windows and Linux
- Installing authentication packages
- Editing PAM and SSH configuration files
- Configuring one-time-password authentication
- Managing Linux services
- Verifying configuration changes and generated files

## Completion Evidence

[View completion report](./completion-report.pdf)
