This script update a dynamic DNS entry from your external IP address

Make an API_KEY in the Memset control panel.  This will need to have
these permissions at minimum.

  dns.zone_domain_list
  dns.zone_info
  dns.zone_record_update
  dns.reload
  job.status

Pass in API_KEY and HOSTNAME and this script will set the HOSTNAME to
have your current external IP address.

Further info: 

 - Article about this program: https://www.memset.com/blog/dynamic-dns-api-example/
 - Memset API Docs: https://www.memset.com/apidocs/
 - Memset DNS manager: https://www.memset.com/docs/control-panel/dns/
