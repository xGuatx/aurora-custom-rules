# auroraCustomRules

Custom Sigma rules for Aurora agent.

## Custom Additions

- `proc_creation_win_hktl_netexec_nxc.yml` detects NetExec/nxc tool usage including zerologon module.
- `proc_creation_win_hktl_responder_python.yml` detects the Responder python script.
- `proc_creation_win_hktl_msfvenom.yml` detects payload generation with msfvenom.
- `proc_creation_win_hktl_ssh_dynamic_fwd.yml` detects use of SSH dynamic
  port forwarding to create a SOCKS proxy.

- Updated `proc_creation_win_hktl_impacket_tools.yml` to include `smbclientng`.
