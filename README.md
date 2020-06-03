The project is to create an openVPN Ubuntu Server in AWS using Cloudformation

Instructions to deploy the VPN Server.

1. Download the CF_OpenVPN_Server.yaml to your computer.
2. Run CF_OpenVPN_Server.yaml from your AWS Cloudformation console.
3. Input the below parameter
 - Stack Name
 - Instance type
 - VPN Username
 - VPN Password
 - VPN Passphrase for IPSEC PSK
 You can use default values for the rest parameters
 4. The Stack will be created & Initialed in about 5 minutes.
 5. Check the VPN Server instance's public IP from the stack output or from EC2 console
 6. Connect a VPN client to this VPN Server.
