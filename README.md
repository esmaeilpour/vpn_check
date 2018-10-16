# vpn_check
ping vpn server for lowest latency

# Requirement
  https://fping.org/fping.1.html

cronjob
0 * * * * check | cat <(date) <(cat -) > /var/log/vpn_check
