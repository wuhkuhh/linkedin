## Common Issues & Fixes

This section documents recurring issues encountered in the home lab environment and the steps taken to diagnose and resolve them.

---

### Service Not Reachable (FTP / SFTP / IRC)
**Symptoms**
- Connection timeouts
- Service reachable locally but not remotely
- Authentication failures

**Troubleshooting Steps**
- Verified service status and listening ports
- Checked firewall rules and port forwarding configuration
- Reviewed service logs for authentication or permission errors
- Confirmed user permissions and directory access

**Resolution**
- Corrected firewall and port forwarding rules
- Restarted affected services after configuration changes
- Updated user permissions and authentication settings

---

### Virtual Machine Performance Issues
**Symptoms**
- Slow boot times
- High CPU or memory usage
- Unresponsive services within VM

**Troubleshooting Steps**
- Reviewed resource allocation (CPU, RAM, disk)
- Checked host system utilization
- Inspected VM logs and system processes
- Tested with snapshots and rollback where applicable

**Resolution**
- Adjusted VM resource allocation
- Optimized background services
- Rebuilt or restored VM from snapshot when necessary

---

### Network Connectivity Problems
**Symptoms**
- Inconsistent connectivity
- Inability to reach external services
- DNS resolution failures

**Troubleshooting Steps**
- Verified IP configuration and gateway settings
- Tested DNS resolution and connectivity using command-line tools
- Reviewed router and network configuration
- Checked for conflicting IP assignments

**Resolution**
- Corrected network configuration errors
- Updated DNS settings
- Restarted network services and devices as needed

---

### Website Availability or Configuration Issues
**Symptoms**
- Website not loading or returning errors
- Incorrect content displayed
- SSL or domain-related warnings

**Troubleshooting Steps**
- Verified web service status
- Checked configuration files and file permissions
- Reviewed domain and DNS settings
- Examined server logs for errors

**Resolution**
- Corrected configuration and permissions
- Restarted web services
- Updated DNS records or site settings

---

### Backup or Cloud Sync Failures
**Symptoms**
- Incomplete or failed backups
- Data not syncing as expected
- Permission or authentication errors

**Troubleshooting Steps**
- Verified storage paths and access permissions
- Checked authentication credentials
- Reviewed sync and backup logs
- Tested manual transfers for validation

**Resolution**
- Corrected permissions and credentials
- Adjusted backup schedules or configurations
- Verified successful data transfer and integrity

---

## Troubleshooting Approach
Across all issues, a consistent troubleshooting methodology was applied:
1. Identify and isolate the problem  
2. Gather relevant information and logs  
3. Test potential causes methodically  
4. Apply targeted fixes  
5. Verify resolution and document changes  
